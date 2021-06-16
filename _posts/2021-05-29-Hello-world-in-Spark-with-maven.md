---
layout: pages
title: "Spark Hello World with maven"
excerpt: "Learn word count program in Spark using Maven as build tools"
toc: true
toc_label: On This Page
toc_icon: list
# toc_sticky: true
share: true
tags:
  - spark
  - hello world
  - big data
  - maven
category:
  - spark
---

This post covers the basic spark set up and run the hello world program i.e. the word count using Spark and maven.

## Prerequisites
1. Scala - Basic
2. Intellij IDE - Basic
3. Maven installed in your system
4. Java 8 installed in your system

## 1. Create a maven Project
1. Create a Maven Project using the intellij Idea new project 
2. under src/main create a new folder called scala.
3. Mark scala directory as source

## 2. Add the maven dependencies
Add the below dependencies and build plugins in your pom.xml
<script src="https://gist.github.com/bimanmandal/00c823e7a08c557520e1397085f6fdc0.js?file=pom.xml"></script>

## 3. Create a scala object
Create a scala object ApplicationMain.

## 4. Write the hello world code
Under your `ApplicationMain` object, create a main method and write the below code
<script src="https://gist.github.com/bimanmandal/00c823e7a08c557520e1397085f6fdc0.js?file=ApplicationMain.scala"></script>

## 5. Run the program locally
Run your spark application by right clicking the ApplicationMain and check the output in your console.

The code is available in [Github](https://github.com/bimanmandal/learning-spark/tree/main/hello-world-spark-maven){:target="_blank"}

