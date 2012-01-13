---
safe: true
layout: post
category: development
tags: windev
---

On a project, i was requiring to write a XML editor (kind of), and i was
requiring to be able to copy entire nodes with it's subchilds and allow the
user to paste it on another node.

Searching on the help, i found that there is no native functionality to achieve
this. This feature was not required by the end user, but by me, because
after completing this editor i would need to use it to create some very complex
logic in it.

So, here's what i've come up...

## First, save the node

First of all, we need to save a node with all it's childs in a string.

The column delimiter will be the ASCII character 1, and the row delimiter will be ASCII character 2.

So, given a row index, i want to copy the row and it's childs, preserving hierarchy, into memory, so i can paste it later.

<script src="https://gist.github.com/1608418.js?file=gistfile1.txt"></script>

## Then, we need to Paste the row

We need to consider two cases, one when we want to paste the node as a sibling
of another node given a position, or as a child of another node.

So, we will be have the following function...

<script src="https://gist.github.com/1608418.js?file=gistfile1.txt"></script>

You'll see some weird code at the start to get `nRelPos`. That's because `TableInsertChild` takes as third parameter the child's relative position.

## That's it...

That's pretty much all!

Wasn't that hard... Just use `CopyTreeNode` to copy the node into memory. You can use `ToClipboard` to put the node on clipboard.

Then, just use `PasteTreeNode` to paste it. You can read it from `Clipboard()` also, or from a local variable.

You may offer two options for the paste function: Paste as Sibling, or Paste as Child, and send the proper parameter to `PasteTreeNode`.

Hope you find this handy.

