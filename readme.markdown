About DTBonjour
==================

DTBonjour had its origin when I wanted communicate between a Mac app and an iOS app. It greatly simplifies networking over WiFi by giving you an easy method to transmit any NSObject that conforms to NSCoding.

License
------- 
 
It is open source and covered by a standard BSD license. That means you have to mention *Cocoanetics* as the original author of this code. You can purchase a Non-Attribution-License from us.

Documentation
-------------

Documentation can be [browsed online](http://cocoanetics.github.com/DTBonjour) or installed in your Xcode Organizer via the [Atom Feed URL](http://cocoanetics.github.com/DTBonjour/DTBonjour).

Here is a [tutorial](http://www.cocoanetics.com/2012/11/and-bonjour-to-you-too/) on how to build a simple chat app with DTBonjour.

Usage
-----

You have these options of including DTBonjour in your project

- DTBonjour on CocoaPods
- include the git repo as a submodule
- clone a copy of it into an Externals folder in your project tree

When not using CocoaPods these are the steps for setup:

- include the xcodeproj as a sub-project
- Add the ObjC and all_load linker flags
- add a dependency to the static library for your platform
- add the static library also to the linking phase
- add a User Header Search Path into the location where you have the code