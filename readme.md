
### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
--> 
   getElementById: Used to find an element with specific id .It is an object.

   getElementByClassName: It's used to find more element with a specific class name. It is a HTMLCollection.

   querySelector: It's used to find element like CSS selector. It's give the first element and it is an object.

   querySelectorAll:It's used to find more element with CSS selector. It's give a NodeList. 




2. How do you **create and insert a new element into the DOM**?
-->
first i need to create an element, then set attribute and appendChild() 




3. What is **Event Bubbling** and how does it work?
-->
   We used Event Bubbling for handling the event in DOM.




4. What is **Event Delegation** in JavaScript? Why is it useful?
--> 
   Event Delegatiion is a technique. By using this we can control child element by placing Listener in parent element.
   By using Event Delegation we can habdle element by less code.



   
5. What is the difference between **preventDefault() and stopPropagation()** methods?
-->
   preventDefault(): It's stop the behavior of an element.
   stopPropagation(): It's stop the event going to the parent.

