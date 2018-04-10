# INFO 448 Mobile Development Android

## About this guide

This repository aims to provide invaluable tips, advice, and resources in alignment with what's being presented during lecture. After each lecture or a homework has been assigned, come check out this repo for some good gotchas!

Something interesting you want to point out or let me cover on, submit an issue to this repository. Or, send me an email: **naruthk@uw.edu**.

---

## Table of Content

<!-- TOC -->

- [INFO 448 Mobile Development Android](#info-448-mobile-development-android)
  - [About this guide](#about-this-guide)
  - [Table of Content](#table-of-content)
  - [Topics](#topics)
    - [Kotlin Basic](#kotlin-basic)
    - [Kotlin Style Guide](#kotlin-style-guide)
    - [Android Core Concepts](#android-core-concepts)
    - [Lecture: Going Beyond](#lecture-going-beyond)
    - [Homework Hints](#homework-hints)
    - [Lab Meetings](#lab-meetings)
    - [Libraries](#libraries)
      - [Dagger 2](#dagger-2)
      - [Firebase](#firebase)
      - [React Native](#react-native)
      - [Flutter](#flutter)
      - [RxJava](#rxjava)
    - [Resources](#resources)
      - [Articles/Websites on Android Development](#articleswebsites-on-android-development)
      - [Core Documentation](#core-documentation)
      - [Videos/Courses](#videoscourses)
      - [Editors](#editors)
        - [IntelliJ IDEA](#intellij-idea)
        - [Android Studio](#android-studio)
        - [VS COde](#vs-code)
      - [Testing Your Application / Code](#testing-your-application--code)
      - [Publishing Your Application to the Google Play Store](#publishing-your-application-to-the-google-play-store)
      - [Popular Open-Source Android Apps](#popular-open-source-android-apps)
    - [Common Questions](#common-questions)
      - [Troubleshooting](#troubleshooting)
      - [Common Git Issues](#common-git-issues)

<!-- /TOC -->

---

## Topics

### Kotlin Basic

In progress.

---

### Kotlin Style Guide

- Kotlinlang.org's [Coding Conventions](https://kotlinlang.org/docs/reference/coding-conventions.html): It offers the current coding style guide for the Kotlin language.
- Android's [Kotlin Style guide](https://android.github.io/kotlin-guides/style.html): Google's very own style guide for writing Kotlin for Android development
- Ray Wenderlich's [Kotlin Style Guide](https://github.com/raywenderlich/kotlin-style-guide): Another recommended one. Beyond his style guide, he posts lots of useful content on Kotlin too.

---

### Android Core Concepts

- [Activities](concepts/Activities.md)
- Adapters
- [Android](concepts/Android.md)
- Android Emulator
- Android Manifest
- [Architecture](concepts/Architecture.md)
- APK
- Components
- Concurrency
- Fragments
- [Gradle](concepts/Gradle.md)
- Graphics
- Intents
- [Instant Run](concepts/Instant_Run.md)
- [Kotlin](concepts/Kotlin.md)
- Layouts
- Location
- Logging (Debugging)
- Material Design
- MVP (Model-View-Presenter)
- Permissions
- Providers
- Resources
- Storage
- Views
- [XML](concepts/XML.md)

---

### Lecture: Going Beyond

- Week 1: March 27th and 29th
  - Links:
  - Code:
- Week 2: April 3rd and 5th
  - Links:
  - Code:
- Week 3: April 10th and 12th
  - Links:
  - Code:

---

### Homework Hints

Aside from external links that you might be finding useful to help you tackle through the homework assignments, there are also coding/concept hints to lead you to the correct direction.

- Homework 1: **Hello, World**
- Homework 2: **Simple Kotlin**
  - Running test script: 
    - `kotlinc -script main.kts`
    - Before running the code, make sure you are inside the directory in which your `main.kts` file is stored.
    - See troubleshooting questions at the bottom of this page for more details if you've discovered an error running the script file.
  - `debugString`:
    - Make sure you understand the purpose of this read-only String.
    - [Getters and Setters - Koltin](https://kotlinlang.org/docs/reference/properties.html)
- Homework 3: **Complex Kotlin**
  - Running test script:
    - `kotlinc -script main.kts`
    - Before running the code, make sure you are inside the directory in which your `main.kts` file is stored.
  - Woring with higher-order functions and lambdas:
    - [Higher-Order Functions and Lambdas - Kotlin Programming Language](https://kotlinlang.org/docs/reference/lambdas.html)
      - Take note of things like `invocation`, `lambda expressions`, `anonymous functions`, `passing a lambda to the last parameter`.
    - [Higher-order function - Wikipedia](https://en.wikipedia.org/wiki/Higher-order_function)
    - [Programmer Dictionary: Higher Order Function](https://blog.kotlin-academy.com/programmer-dictionary-higher-order-function-9cadb07df94e)
      - The author provides useful examples of how to use functions such as `.map {}` and `.filter {}` that might be beneficial for you
  - Note the difference between `listOf(12..20)` and `listOf(12,13,14,15,16,17,18,19,20)` and just plain `(12..20)`. Find out their differences.
  - Fizzbuzz puzzle? [What is the FizzBuzz puzzle?](http://wiki.c2.com/?FizzBuzzTest)
  - Repeating strings? The `repeat(x)` function might be useful in certain cases.
  - Enumerators: [Enum Classes - Kotlin](https://kotlinlang.org/docs/reference/enum-classes.html)
  - `.invoke()` function: [Invoke - Kotlin](https://kotlinlang.org/docs/reference/operator-overloading.html#invoke)
  - Stackoverflow - [Why .fold() and why not .reduce()?](https://stackoverflow.com/questions/44429419/what-is-basic-difference-between-fold-and-reduce-in-kotlin-when-to-use-which)
- Homework 4:

---

### Lab Meetings

- Week 1: March 28th
  - Slides:
- Week 2: April 4th
  - Slides:
- Week 3: April 11th
  - Slides

---

### Libraries

#### Dagger 2

In progress.

#### Firebase

In progress.

#### React Native

Before diving in to what React Native really is, read this article I've written on [Native vs. Non-native Apps](articles/Native_Non-native.md)

In progress.

#### Flutter

In progress.

#### RxJava

In progress.

---

### Resources

#### Articles/Websites on Android Development

- [Learning android development](https://android.jlelse.eu/learning-android-development-e2d4d239a7a3)
  - Meant for people starting Android Development, or anyone needing more resources and foundation to go on and make great apps
- [Android Development Best Practices](https://blog.mindorks.com/android-development-best-practices-83c94b027fd3)
  - Best practices in designing and developing Android apps
  - Cover topics like Model-View-Controller, unit testing, debugging tools, HTTP library, Fragments, RxJava
- Professor Joel Ross's [Android Development: Lecture Notes](https://info448-s17.github.io/lecture-notes/) are super great and useful, but I think it's a bit too formal and technical. He teaches this course many times before.

#### Core Documentation

- [Android Development Documentation](https://developer.android.com/guide/index.html)
- [Kotlin Documentation](https://kotlinlang.org/docs/)
- [Java API Documentation](http://docs.oracle.com/javase/8/docs/api/)

#### Videos/Courses

- YouTube - [Android App Development for Beginners Playlist](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBsvRxJJOzG4r4k_zLKrnxl)
  - Really good basic-to-intermediate introduction to Android development.
- Udemy - [60 Minutes with Kotlin for Developers](https://www.udemy.com/kotlin-for-developers)
  - You'll have to paid for this course, but it does a really good job of getting right to the point and explaining all the important bits you'll need to master Kotlin in just an hour.

#### Editors

##### IntelliJ IDEA

In progress.

**Setting up:**

**Plugins:**

##### Android Studio

In progress.

**Setting up:**

**Plugins:**

##### VS COde

In progress.

#### Testing Your Application / Code

In progress.

#### Publishing Your Application to the Google Play Store

In progress.

#### Popular Open-Source Android Apps

In progress.

---

### Common Questions

#### Troubleshooting

**Hey Sam, I've uploaded my solution to my GitHub repo. But how do I test what I've uploaded to make sure it's working?**

That's easy! Clone the repo to a new directory. Now build the app. If you're working on an Android app, then test the app using one of your emulators.

There's a catch! When you open an existing Android project in Android Studio, sometimes you will need to press the `Sync with Gradle` button in order for the project to actually be properly running. Otherwise, your app might not run!

**I'm using VS Code for one of the assignments. Where's the Integrated Terminal I saw you and Ted used during lecture?**

![](images/integrated_terminal_button_vccode.png)

You can reach the Integrated Terminal in two ways:

1. If in your VS code, you can’t find the Integrated Terminal panel,  head to `View` -> `Integrated Terminal`

2. Click on either the circular X symbol or the triangular Warning symbol. Then switch to the `Terminal` tab.

You're set! Now you can run the exact bash script inside this terminal.

**The test script isn't working! What do I do?**

If, for instance, `kotlinc` isn’t installed, then you’ll have to find a way to install it first.

For Mac, do it through Homebrew:
1. Make sure Homebrew is updated: `brew update`
2. Install Kotlin compiler: `brew install kotlinc`

For Windows machines, refer to the [official installation guide](https://kotlinlang.org/docs/tutorials/command-line.html).

---

#### Common Git Issues

**What do I do when I get this error: `Updates were rejected because the remote contains work that you do not have locally. This is usually caused by another repository pushing`?**

When you created your repository, there happens to be a `README.md` file already inside of it. And so when you do a `git push`, git will not allow you to do it. That’s because you are trying to push something locally that is “behind” what’s inside the remote repository.

To fix the problem, a simple way is to delete that repo from GitHub. Create a new one of the same name (but this time, don’t let GitHub create a README file for you). Then follow Ted’s instruction to re-route your remote URL, and `git push` should work.

**Do you suggest using a GUI for connecting and utilizing GitHub or should I stick with using the command line interface?**

How you want to upload it to GitHub is entirely up to you. For me personally, I’d rather tick with the command line interface (but it's my preference).

As long as your code solution is able to be uploaded to GitHub's cloud servers, everybody is happy.