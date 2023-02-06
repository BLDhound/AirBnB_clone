# AirBnB_clone project
## First step: 
Write a command interpreter to manage your AirBnB objects.
This is the first step towards building our first full web application: the AirBnB clone. This first step is very important because we will use what we build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help us to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of our future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine

## What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Update attributes of an object
Destroy an object

## Idea
The concept can be illustrated with the image below

![image](https://camo.githubusercontent.com/91879364d64b9f1236b698c4630bdc694c870f879f5b546612c376f18b5a36b0/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f696e7472616e65742d70726f6a656374732d66696c65732f636f6e63657074732f37342f68626e625f73746570332e706e67)

## Description

```
+ How to start it
+ How to use it
+ Examples
```
