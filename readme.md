# React Native Intro

A workshop and introduction to react native.

![](https://facebook.github.io/react-native/img/opengraph.png)

## Objectives

* Describe what react native is useful for
* Use flexbox to style a react native app
* Get data from an api using fetch
* Intro to navigation using react-navigation

## React Native: Background

#### What is React Native?

React native is a framework for writing applications for mobile platforms.  The language you will primarily write in is JavaScript.  The framework allows you to quickly build and iterate on an application.

The project was created by Facebook after it launched react for the web.  It also has tremendous community support, with tons of open source contributors.

#### Why React Native?

__Advantages__

* Shared code between iOS and Android
* More JS developers available than native developers
* Faster iteration when developing (hot reloading, easier to reason about state)
* Can prototype quickly

__Disadvantages__

* Not as performant as native
* Fast paced community.  Lots of change

#### How is React Native Different?

The react ecosystem is described as a learn once write anyone framework.  In other words, code may be slightly different on different platforms (web vs iOS vs android), but the fundamental ways that you build a react app are the same.  And hopefully many components that you create can be shared across the platforms.

This philosophy is in contrast to other frameworks like [Apache Cordova](https://cordova.apache.org/) that have tried to be a _write_ once and run anywhere framework.

The main difference between the two approaches is that react native apps actually compile down to native code.  In other words, the react native app that you create is very similar to implementing a native application on iOS or android.  In Cordova however, most of your code is run in a web view inside of a native container, so fundamentally, you are trying to make a webpage look like a mobile app.

