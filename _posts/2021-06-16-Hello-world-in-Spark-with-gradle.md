---
layout: pages
title: "Spark Hello World with Gradle"
excerpt: "Learn word count program in Spark using Gradle as build tools"
toc: true
toc_label: On This Page
toc_icon: list
# toc_sticky: true
share: true
tags:
  - spark
  - hello world
  - big data
  - gradle
category:
  - spark
---

## Prerequisites
1. Scala - Basic
2. Intellij IDE - Basic
3. Gradle installed in your system
4. Java 8 installed in your system

## 1. Create a gradle Project
1. Create a Gradle Project using the intellij Idea new project.
2. Create a new folder called src/main/scala
3. Mark scala directory as source

## 2. Add the gradle dependencies
Add the following code in your build.gradle
<script src="https://gist.github.com/bimanmandal/88a3e168c962bcbf2d4b5709cf4fb3a0.js?file=build.gradle"></script>

## 3. Create a scala object
Create a scala object ApplicationMain.

## 4. Write the hello world code
Under your `ApplicationMain` object, create a main method and write the below code
<script src="https://gist.github.com/bimanmandal/00c823e7a08c557520e1397085f6fdc0.js?file=ApplicationMain.scala"></script>

## 5. Run the program locally
Run your spark application by right clicking the ApplicationMain and check the output in your console.

The code is available in [Github](https://github.com/bimanmandal/learning-spark/tree/main/hello-world-spark-gradle){:target="_blank"}

