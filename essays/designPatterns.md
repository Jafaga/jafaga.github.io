---
layout: essay
type: essay
title: "Crafting Code: The Blueprint for Software Coding"
date: 2024-12-05
published: true
labels:
  - Reflection
  - Design Patterns  
---

<img width="400px" class="rounded float-start pe-4" src="../img/designPatterns.png">

Imagine you're building a hourse with any sort of plan. You might gather bricks or wood together, hoping that it will hold up everything. Though in the end, the result will most likely lead the house to be messy looking, and perhaps it might fall apart one day without proper structure. And that my friend is why we need blue prints for building, which they help engineers design things that are functional, durable, and adaptable for future use. In another case, software engineering has this thing called <b>design patterns</b>, which are those blue prints. They're a kind of strategic way for solving common problems, helping us create systems that is efficient, reliable and easy to understand. 

Design patters are not the typical copy and pasting, as they provide the framework of our thinking to a problem. Similar to how different types of buildings require different designs, software problems call for different patterns. 

## Putting Patterns to Work

### Elevator Logic: 
Building a web application where the user interface needed to switch between different states, as in loading, success, and error. Handling this without a plan could have led to a big miss of if-else statements. That is where a <b>state pattern</b> comes in handy, which is like designing an elevator. An elevator has multiple states: moving up, moving down, or staying in one place. Each state behaves differently, which by using this pattern helps organizes the state into different classes, making the coding procedure easier to manage and understand.

Design patterns are not just about copying and pasting code, but rather about providing a framework for how we think about and apporaching something. Just as different types of builindgs, like skyscrapers, bungalows, or stadiums require different designs, which aa software problems have different approachable concpets to implement and structure a solution. 

### The Enemy Factory: 
Another approach is when working on a game that needs to create different types of enemies, which each of them has a unique behavior and attribute. Instead of writting separate code for every enemy, you may use a parrtern called <b>factory method pattern</b>. It is like an assembly line in a factory where each station produces a type of product based on a blue print. This approach allows to generate different enemy types, making it easier to add new ones later without rewritting everything. 

### Singleton for Database Connections: 
One last practical example is managing database connections in an application. Opening multiple connections simultaneously can lead to slow performance. A pattern called <b>singleton pattern</b> solves this problem which ensures only one instance of a database connection is created and shared. This is basically like having a master key to access a building. This not only optimizes resource usage, but also prevvents errors caused by multiple conflict connections. 

## Why Patterns Matter 
Design patterns are not theoretical ideas, as they are practical tools shaped by experienced developers who've solved the same problems we face today. Using them feels like having a cheat code to write a smarter, cleaner, and more reliable software. 

In my experience, applying patterns like the state, factory, or singleton patterns have transformed the way I approach coding issues. These patterns make the code look more organized and easier to understand, which is much easier to maintain as well. They are not just about solving problems on the spot, but about creating solutions that is in good quality. 

## The Art Perspective of Crafting Code 
Embracing design patterns is more than just a practice, but it’s a mindset shift the way how I would see things. Learning how to construct code that is not only functional but also neat and professional. When you use design patterns, you’re not just writing code, you’re building something that can change over time. It’s about thinking ahead and designing for the future, ensuring your software can stand strong even as the requirements change.

So, the next time you sit down to solve a coding problem, think of it as designing a house. Will you throw things together haphazardly in a rush manner, or will you take the time to create a blueprint, laying a solid foundation for something that can hold? Design patterns are your tools to craft not just software, but a legacy of how things are developed and built.







