---
layout: post
category: development
tags: development windev c++ opensource
---

Yes, i'm still alive... With a lot of work to do.

Over a year without a post, i know, last post i said i will post more frequently.

Over the past years, i've lost lots of pet projects because of hard drives failures.

I wish to say "not anymore", but it happened to me last week again.

I've bought 3 new 1 GB hard drives to store all my projects, but still, i don't
trust them.

So, today i've created a public WinDev SCM, that will contain all my pet projects.

All projects are made with WinDev 17, but you can download them with any newer
version of WinDev (18 or 19).

Here's the information of the SCM:

 - SCM Server: wdoss.wolfbit.com
 - SCM Port: 4900
 - SCM User: GUEST
 - SCM Password: GUEST
 - You need to start WinDev with "GUEST" as your User Name.

Every project here is Open Source, but i'm beware that i'm not responsible for any
damage that the software may cause to anyone. It's free, for personal or commercial
use.

I haven't placed every pet project there. Right now these are the only projects up:

 - LmDbSaver. It's a layer and utility classes for the [LightningDB](http://symas.com/mdb/) database. On the current project i'm on, this guy saved my ass. It's a ultra fast key-value database. When you need a really big and fast database and you don't need SQL, then this is your guy. It allowed me to handle huge data sets (over 30 GB of data) and process it. HyperFile is good, but it couldn't handle the data. MS SQL Server was very slow for the task, so, this guy kicked in and saved the day.
 - SyperSample. This is a sample project that uses the Syper Web Development Tools being developed by me. I'll make another post for SWDT, but for now, just know that if you get this it will not work because you need to configure Apache or nginx. I'll make another post for that. Basically it's a Web Application made on WinDev without using WebDev.
 - WDSQL. This is the WD Power SQL project. I've made other posts about this project. Just download it and hit GO, it'll just work. The new version supports SQL Server, PostgreSQL and other databases.
 - ZeroMQ. These project is badass. It includes several projects inside it. First of all, it includes [ZeroMQ](http://zeromq.org/) bindings for WinDev and utility classes. ZeroMQ is a library that allows you to make distributed systems very easily. This project also includes the XmlRenderer and JsonRenderer classes, that allows you to convert almost any data type of WinDev into an XML or JSON string. Very useful for Web Development. Also, in this project you will find the SimpleQuery utility class, that allows you to create SQL queries without using SQL (what???). It's hard to explain SimpleQuery until you need it, but it's the way i make queries now on WinDev. It currently supports PostgreSQL, SQL Server and HyperFile with more drivers to come. And lastly, this project contains the Syper Web Development Tools, which i'll explain in the future in another post, because it's a big project.
 
Hope you like it.
