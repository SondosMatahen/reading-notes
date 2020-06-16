# Read 08 in 201
<br/>

## From the Duckett HTML book:
<hr/>

1. Chapter 7: “Forms” 
 * Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.
 * There are several types of form controls that you can use to collect information from visitors to your site
   1. Adding tEXt
   2. making Choices
   3. submittgng Forms
   4. uploading FIlEs
* Form controls live inside a <form> element. This element should always carry the action attribute and will usually have a method and id attribute too.

* action Every <form> element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

* method Forms can be sent using one of two methods: get or post.
* HTML5 introduces new form elements which make it  X easier for visitors to fill in forms.
<br/><br/>

![img](https://cdn.educba.com/academy/wp-content/uploads/2019/06/html15.png)
<br/><br/>

![img](https://i.ytimg.com/vi/MKSQYsLLFEo/maxresdefault.jpg)
<br/><br/>

2. Chapter 14: “Lists, Tables & Forms” (pp.330-357)
 * There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.
 * The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker)
 * You can specify an image to act as a bullet point using the list-style-image property
 * Lists are indented into the page by default and the list-styleposition property indicates whether the marker should appear on the inside or the outside of the box containing the main points.
 <br/><br/>

 ![img](https://idg.net.ua/blog/wp-content/uploads/list-style-type-css-screenshot.png)
 <br/><br/>

 * :hover to highlight a table row when a user's mouse goes over it
* If you have empty cells in your table, then you can use the empty-cells property to specify whether or not their borders should be shown
* The border-spacing property allows you to control the distance between adjacent cells. By default, browsers often leave a small gap between each table cell, so if you want to increase or decrease this space then the border-spacing property allows you to control the gap.
* text-shadow can give a 3D look to the text in browsers that support this property.
* The cursor property allows you to control the type of mouse cursor that should be displayed to users.
* Forms are easier to use if the form controls are vertically aligned using CSS.
<br/><br/>

![img](https://agirlandhermac.design/resources/wp-content/uploads/Screen-Shot-2017-11-12-at-1.31.13-PM.png)

<br/><br/><br/>

## From the Duckett HTML book:
<hr/>

1. Chapter 6: “Events” (pp.243-292)
  * When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events
  * When an event occurs, the event object tells you information about the event, and the element it happened upon
  * Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element
  * The event object has methods that change: the default behavior of an element and how the element's ancestors respond to the event.
  * The mouse events are fired when the mouse is moved and also when its buttons are clicked. 
  <br/><br/>
  ![img](data:image/png;base64,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)
  <br/><br/>
 

