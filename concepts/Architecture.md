# Architecture

Since this course is all about developing an app, we will not go too deep into the architectural side of things. But as a developer, it's important to get a sense of major components that form the Android architecture. Your phone and the apps you use actually do a lot more than what's on the surface.

There are 6 major components for the Android Platform.

1. System Apps
2. Java API Framework
3. Native C/C++ Libraries
4. Android Runtime
5. Hardware Abstraction Layer (HAL)
6. Linux Kernel

![Android architecture. Image by Wikimedia Commons](/images/architecture.png)

Rather than going up the stack of architecture components, let's start from the top and go down each one.

## System Apps

The Camera app that comes with your phone belongs to this component. Any built-in application that comes with your phone, such as the Messaging app, Browser app, and the Email app counts too.

Systems apps are useful because they **benefit both users and developers**. Users use system apps like the Camera app to take capture beautiful photos. Developers rely on the Camera app so that they do not need to build that functionality by themselves.

## Java API Framework

APIs are like individual Lego pieces. You connect a bunch of pieces together (calling the API) and create something big like a house (building your app).

As a developer, Android has provided you with lots of framework APIs to take your app to a whole another level. It's also good to know that frameworks handle the task of interacting with the hardware for us.

## Native Libraries / Android Runtime

By "native", we mean Android system components and services that are built by C and C++. Yes, Android is written in Java but not entirely! You'll be using Java to write apps. But often times you'll be working with APIs that utilize native libraries that are actually written in C and C++ for faster performance.

Alongside native libraries is the **Android Runtime** or **ART**. Think of it like multiple virtual machines running at once to help make sure that the phone and the app you're using run smoothly.

For more details about ART, read this Medium [post](https://android.jlelse.eu/closer-look-at-android-runtime-dvm-vs-art-1dc5240c3924).

## Hardware Abstraction Layer

The ATM itself is like the **Hardware Abstraction Layer**, or HAL. HAL directly accesses the hardware, such as the camera and disc storage and provides you with access to hardware components when you call a framework API.

When you withdrew money from the ATM, you don't actually see how money came out of the cash dispenser. The ATM did the job for you, just like how HAL connected your API to the hardware for you.

## Linux Kernel

If the Linux Kernel is a team, then this team is behind everything we've learned. This hard-working team makes sure that our phone and apps we use run smoothly by utilizing as many people as possible to do things at once(threading and low-level memory management).

So it's safe to say that your Android phone is a Linux computer!