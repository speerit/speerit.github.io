---
layout: post
title:  "Classes"
date:   2015-03-29 18:36:48
categories: technical
---

Today we are going to discuss classes. Classes are a way to distribute characteristics. By this I mean that I can apply the same features to different objects if they belong to the specific class. For example, an array is a part of the class Array. Because of this, I can manipulate the array with methods are a part of the Array class. I'm going to explain this better by creating a sample class here.

<img src="../imgs/my_class.png" alt ="my class in ruby">

I've created a class called Cars. It has the instance variables @manufacturer, @model, @year, and @color. This means that they are variables that are a part of the class Cars, but have different values for each instance of cars. I'm going to create two cars down below and apply different values to the variables. Additionally, use the attr_accessor attribute which means I can return and change the value of a variable.

<img src="../imgs/our_cars.png" alt ="our cars in ruby">

See, I was able to create two car objects with this data structure. This class is used to mimic real world objects! Now that I have the cars created, I can figure out what they are outside of the class. I can also manipulate the variables, for example, if I got a new car.

<img src="../imgs/manipulation.png" alt="manipulation">

And here it what I get when running the program.

<img src="../imgs/terminal.png" alt="terminal">
