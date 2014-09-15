## Lab 01 : Getting started with front-end development

### Demo

Have a look at this [screencast](https://www.youtube.com/watch?v=F6HcVrZTaVs) to see a demo of the application that you will implement in this lab.


### Objectives

* Setup the first version of your **development environment**. You will have to select, install and configure an **editor**, a **browser** and **developer tools** (**console**, **debugger**, etc.).


* Do **experiments with JavaScript**. You will have to play with **variables**, **objects**, **functions**, **constructors**, **prototypes**, etc. 


* Experiment with a couple of JavaScript libraries, including **JQuery** and **handlebars**.

### Deliverables

At the end of this lab, you should have produced:

* A **working web page** that reproduces the behavior shown in the demonstration. You will be asked to do a demonstration and to explain how you have implemented the features of the app.


* A **presentation**, with answers to the questions listed in the following task list.


* The code and the presentation should be stored in a **Github repo**. Send me an e-mail with the URL of this repo.

### Tasks

#### Task : Design and setup your development environment
* Which IDE or editor did I install?
* How did I configure it (extensions, plugins, etc.)?
* Which browser and developer tools did I install?

#### Task : Create a simple web page
* How do I use Bootstrap in a web page?
* How do I use a template built on top of Bootstrap?

#### Task : Integrate JQuery and implement the clock
* How do I integrate JQuery in a web page?
* How do I select and manipulate DOM elements with JavaScript?
* How do I execute a function on a regular basis?
* What does the following code do and what is the ```$``` sign? 

```js
$(function(){
  console.log("What happened here?");
});
```

#### Task : Implement the "Show alert" button 
* How do I attach an event handler to a DOM element with JQuery?

#### Task : Display the mouse coordinates in the DOM (in the footer)
* How do I track mouse movements with JQuery?
* How do I display event properties in a DOM element?

#### Task : Define a Constructor for creating ```Person``` objects
* How do I define a constructor?
* How do I define properties that will be added to all objects created with the constructor?
* How do I define a method that will be shared by all objects created with the constructor?
* How do I create objects with my Constructor?

#### Task : Display ```Person``` objects in the DOM
* How do I use JQuery to update the DOM with the dynamically created objects?
* How do I map the color of the DIV to the gender of the person?
* [*feature missing from the screencast*] How do I add (instead of replacing) a Person to the DIV if the shift key is pressed while the mouse moves?

#### Task : Experiment with the Chance.js library
* How can use the Chance.js library to generate random values for my objects?

#### Task : Load the rooms via AJAX
* How to I create a ```rooms.json``` file to store the rooms information (i.e. what is the content of this file?)? 
* How do I use JQuery to load the ```rooms.json``` asynchronously and to update the DOM?

#### Task : Experiment with the Handlebars.js template engine
* How do I use the handlebars.js template engine to separate presentation and logic in my page?
* How did I use it concretely for this application?

### Resources

* BootStrap: http://getbootstrap.com/
* JQuery: http://learn.jquery.com/using-jquery-core/
* Chance.js: http://chancejs.com/
* Handlebars.js: http://handlebarsjs.com/