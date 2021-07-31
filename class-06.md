# **Understanding the problem domain**
________
*Understanding The Problem Domain Is The Hardest Part Of Programming*

* What is the hardest thing about writing code?

    1.Learning a new technology
    2.Naming things
    3.Testing your code
    4.Debugging
    5.Fixing bugs
    6.Making software maintainable

* Why problem domains are hard?
We should put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

* **Programming is easy if you understand the problem domain**
 * we should  write the code to produce.

* **What can you do about it?**

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

    1.Make the problem domain easier
    2.Get better at understanding the problem domain

You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.
____________

## **WHAT IS AN OBJECT? **
*Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. *

**property:** if a variable is part of an object.tell us about the object, such as the name of a hotel or the number of rooms it has.

**method**: if a function is part of an object,represent tasks that are associated with the object.

**key**: properties and methods.

An object cannot have two keys with the same name. This is because keys are used to access their corresponding values. 

* **Creating an object/Literal notation**

![literal ](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSEQdiDBBc__US_81_0rMDyo-AWdhnrkjLEhQ&usqp=CAU)

![access an object](https://www.bookofnetwork.com/images/javascript-images/JS_Object-literal---Ways-of-accessing-object-property_04Oct16_1421.png)
 
 * *Dot notation vs bracket notation JS*

 ![Dot notation vs bracket notation](https://drek4537l1klr.cloudfront.net/larsen2/Figures/150fig01_alt.jpg)
_____________________

### **Document Object Model**
_________

When the browser loads a web page, it creates a model of the page in memory. The DOM specifies the way in which the browser should structure this model using a DOM tree. 
The DOM is called an object model because the model (the DOM tree) is made of objects.


*  DOM node:Every element,attribute, and piece of text in the HTML is represented.

![domtree](https://info343.github.io/img/html/dom-tree.jpg)

* WORKING WITH THE DOM TREE

  - Accessing and updating the DOM tree involves two steps: 
1: Locate the node that represents the element you want to work with. 
2: Use its text content, child elements, and attributes. 

* How do you query a DOM element?

    1.getElementsByTagName()
    
    2.getElementsByClassName()
    
    3.getElementById()
    
    4.querySelector()
    
    5.querySelectorAll()

    * repeting actions for an entire nodelist 
    Although NodeList is not an Array, it is possible to iterate over it with forEach(). It can also be converted to a real Array using Array.from().

However, some older browsers have not implemented NodeList.forEach() nor Array.from(). This can be circumvented by using Array.prototype.forEach()

* looping through a nodelist

var hotlt ems = document .querySelectorAl l (' l i . hot') ; II Store Nodel ist i n array 
if (hot ltems.length > O) { II If it contains i t ems 
for (var i=O; i<hotl tems.length; i++) { II Loop throug h each it em 
hotltems[i] .className = 'cool'; II Change val ue of class at tri bute 
}}


* TRAVERSING THE DOM

With the HTML DOM, you can navigate the node tree using node relationships

Accessing the innerHTML property is the same as accessing the nodeValue of the first child: 
myTitle = document.getElementById("demo").firstChild.nodeValue;
another way :
myTitle = document.getElementById("demo").childNodes[0].nodeValue;

* PREVIOUS & NEXT SIBLING:
    First. select the parent of the element whose siblings that you want to find.
    Second. select the first child element of that parent element.
    Third. add the first element to an array of siblings.
    Fourth. select the next sibling of the first element.

    ![spilling](https://www.quanzhanketang.com/xml/navigate.gif)



[Back to homw page](https://rahafalbakkar.github.io/Code-201-Reading-Notes)