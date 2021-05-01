# JavaScript

## WHAT IS AN OBJECT?
   Objects group together a set of variables and functions to create a model
  of a something you would recognize from the real world. In an object,
  variables and functions take on new names.

 - In an object, variables are known as properties of the
       object; functions are known as methods of the object.

 -  Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

## Document Object Model

- The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window

* **THE DOM TREE IS A MODEL OF A WEB PAGE**

 
 ![Dom Tree](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/Js-Dom-Tree.png)

* DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes

* You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.

* Whenever a DOM query can return more than one
node, it will always return a Nade list.

* From an element node, you can access and update its
content using properties such as textContent and
innerHTML or using DOM manipulation techniques

* An element node can contain multiple text nodes and
child elements that are siblings of each other.

* In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery)

* Browsers offer tools for viewing the DOM tree .