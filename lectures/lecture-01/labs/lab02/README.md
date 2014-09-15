## Lab 02 : Interactive Visualization of JavaScript Objects

### Demo

Have a look at this [screencast](https://www.youtube.com/watch?v=3VoYl-HHfz0) to see a demo of the application that you will implement in this lab.

### Objectives

* **Get familiar with the JavaScript object oriented model**. You will have to understand what objects, constructors, properties and prototypes are and how to access them programmatically.


* **Get familiar with JavaScript data structures**. You will have to store data in arrays and find ways to access this data efficiently. You will also have to define object structures and to manipulate them.


* See in practice how you can **structure your JavaScript code in modules** and how you can expose methods and data from your modules.


* Have fun with a JavaScript **visualization library**.

### Deliverable

At the end of this lab, you should have produced:

* An ```index.html``` HTML page, displaying an interactive visualization of JavaScript objects.


* A ```myModule.js``` script exposing generic functionality, i.e. the ability to generate a graph data structure (with nodes and edges) based on one or more JavaScript objects.


* A ```myPageScript.js```script, which should create a collection of objects (based on your own constructors), use your module to generate a graph data structure from the objects collection and finally use the third-party visualization library to render the graph.

### Tasks

#### Task : Get familiar with the ```vis.js``` visualization library
* **You will use a third-party library to render the objects graph**. There are many available (one of the most popular is the [D3.js](http://d3js.org) library). To build the demo, I have use the [vis.js](http://visjs.org) library, so you might want to use it as well. Feel free to work with the library of your choice.


* **Get familiar with the library**: have a look at the demos, go through the documentation and have a first look at the code samples. If you decide to use vis.js, then have a look at [this example](http://visjs.org/examples/network/01_basic_usage.html). Check the source of the page to see how the graph was generated. Have a look at [this section](http://visjs.org/docs/network.html) of the documentation.


* **Implement a very basic example**, to make sure that you are able to load the library from your own html page and to render a graph. 

#### Task : Define what the graph should render and how

* **Define what the nodes will represent, and whether there are different types of nodes**. In the demo, I have defined three types of nodes: the **object nodes** (every node represents a JavaScript object), the **own property nodes** (every node represents a property that is defined directly on an object), the **inherited property nodes** (very node represents a property that was inherited from the prototype chain).


* **Define what the edges will represent**. In the demo, I have defined two types of edges: the **prototype edges** (every edge connects an object to its prototype) and the **property edges** (every edge connects an object to one of its properties).


* **Document your design on paper**, so that you have a clear understanding of what you want to draw. Based on this, you will be able to define the data structure that needs to be built from the objects collection and passed to the visualization library.


#### Task : Design the interface for your JavaScript module

* Once your module is initialized, it should be possible to **create a new (empty) objects graph**.


* It should then be possible **add JavaScript objects to the graph**, and your module should take care of adding the corresponding nodes and edges (beware of duplicates).


* Finally, it should be possible to **request the graph data from your module**, in a format that can be used by the visualization library (there is going to be a transformation process from your data structure into the visualization library data structure).


#### Task : Design and implement your module

* Decide how you are going to store nodes and edges in your module. In your **data structure**, you are likely to use JavaScript arrays. But what kind of objects are you going to store in these arrays? How are you going to manage references between edges and nodes?


* Implement the business logic. 


### Resources

* vis.js: http://visjs.org
