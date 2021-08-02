# **class-07**
________________

## Domain Modeling
________________
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

    1.When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
    2.Model its attributes with a constructor function that defines and initializes properties.
    3.Model its behaviors with small methods that focus on doing one job well.
    4.Create instances using the new keyword followed by a call to a constructor function.
    5.Store the newly created object in a variable so you can access its properties and methods from outside.
    6.Use the this variable within methods so you can access the object's properties and methods from inside.
    ![domain modiling](https://cdn.hackernoon.com/hn-images/1*Z2K9hZ9XoCKHHZmN5f0TVw.png)


__________
### **Tabel HTML**
______
The <table> HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.

 ![TABEL](https://slideplayer.com/slide/8112486/25/images/3/HTML%3A+Table+Tag+Attributes.jpg)

 - A table is drawn out row by row. Each row is created 
with the <tr> element.
 - Inside each row there are a number of cells 
represented by the <td> element (or <th> if it is a 
header).
 - You can make cells of a table span more than one row 
or column using the rowspan and colspan attributes.
 - For long tables you can split the table into a <thead>, 
<tbody>, and <tfoot>

________________
#### **Functions, Methods, and Objects**
_________

Object Constructor Notation

In constructor notation, we are creating the same dogs we created in literal notation above, by calling the constructor function with the “new” keyword.
Methods and properties with object literal and constructor notation

Objects in JavaScript have methods and properties, whether they are built with the constructor function or with the literal notation. In JavaScript, the keyword called ‘this’ is the object that “owns” the code. The value of this, when used in an object, is the object itself.
![constract notaion](https://miro.medium.com/max/1838/1*AlFcybVX3m9yXz01LcWa_A.png)


![key](https://www.bookofnetwork.com/images/javascript-images/JS_Slide-156_03Mar17_1117.png)


* **Array**
The JavaScript Array class is a global object that is used in the construction of arrays; which are high-level, list-like objects.
Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.

![array](https://miro.medium.com/max/1130/1*wc0QOYZUVvabyZYVfdzvTQ.png)


* **The window object** is a global object that has the properties pertaining to the current DOM document, which is what's in the tab of a browser. The document property of the window object has the DOM document and associated nodes and methods that we can use to manipulate the DOM nodes and listen to events for each node.

![window object](https://user-images.githubusercontent.com/33088990/32959020-eb853f2c-cbc8-11e7-8184-d5c9f4af8579.png)



* Functions allow you to group a set of related statements together that represent a single task. 


* Functions can take parameters (informatiorJ required to do their job) and may return a value. 


* An object is a series of variables and functions that represent something from the world around you. 


* In an object, variables are known as properties of the object; functions are known as m
ethods of the object. 

* Web browsers implement objects that represent both the browser window and the document loaded into the browser window. 


* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 


* Arrays and objects can be used to create complex data sets (and both can conta in the other).





 [Back to home page](https://rahafalbakkar.github.io/Code-201-Reading-Notes/)