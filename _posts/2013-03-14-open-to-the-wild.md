---
layout: post
category: development
tags: game development ios android c++ emscripten opensource
---

Yes, i'm still alive... And learning a lot lately.

Almost a full year without a post, but here i am again, and i have good news.

Today i'm releasing as Open Source the first version of the complete toolchain
that helped us to build our first game.

We always wanted to release it, since i started coding it, but i wanted to clean
it a bit before releaseing it. The truth is, that i never cleaned the code, and
i think that i never will... So, maybe it's time to release it as it is.

But please, don't judge me to bad for this code, i know sometimes i do very bad
programming, but i'm a good guy in person...

Also, next month will be the aniversary of Anticlon, and we're planning a big
update, with new game elements.

We're also working on a new game, and everything is looking gorgeous, this time
there's a very cute character that i know will charm you.

Also in the next days we'll have the website setup again with great posts from
Seigi Hara.

I haven't created propper readme files for all open sourced projects, but feel
free to grab them and do whatever you like, there will be a very liberal license
in place sometime soon.

You can find the projects at my git repo, or here's the link for each:

 - [layadd](https://github.com/hpcorona/maton-toolchain-layadd) Add layers to a layers file. Used by the compiler toolchain (nailgun) when building a game.
 - [mbd](https://github.com/hpcorona/maton-toolchain-mbd) Convert an XML or layer file into a Machete Binary Dictionary, which is basically a key-value file with support for arrays.
 - [ng](https://github.com/hpcorona/maton-tools-ng) Nailgun, is basically a V8 Javascript interpreter (like node.js but not as complex), but this one is made with the idea in mind of creating complex multiplatform build systems using declarative javascript files. At the moment it only supports Android, but some day it will generate also the XCode project and other stuff... I hope...
 - [stiletto](https://github.com/hpcorona/maton-tools-stiletto) This is a graphical editor tool that let us create and package the graphics for our first game. It's very simple, but it has lots of features... The bad news are that i belive that all the features are useless to other people... I'll try to update it for our new game, for the moment, no code for stiletto are being pushed for a long time because i'm working on a new, more powerful tool... So this is basically deprecated... Feel free to make it your own.
 - [machete](https://github.com/hpcorona/maton-tools-machete) Last but not least, here it is, our platform. My C++ masterpiece, haha, just kidding... Ok, you can look and grab whatever you need, but beware, there are several hacks around that i placed just to make
 it to the deadline. This engine is still being actively developed, and i will be pushing
 massive updates shortly after anticlon's anniversary.

Hope you like it.
