1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans:
getElementById:
1.Id is always unique 
2.Find only one element 
getElementsByClassName:
1.Find elements by using class
2.can return multiple elements
querySelector:
1.Find the first matching element 
2.It's like css select parent than child 
querySelectorAll:
1.finds all matching element
2.return Nodelist

2. How do you create and insert a new element into the DOM?
Ans:To create or inset a new element in the DOM first of all I create element document.createElement() after that I add content innerHTML or innerText than appendChild() or append()

3. What is Event Bubbling? And how does it work?
Event Bubbling is when we first click in an element the event first happens on that elelment and than it goes up to it's parent than it's grandparent and so on 

4. What is Event Delegation in JavaScript? Why is it useful?
Ans: Event Delegation means thst instead of adding event to many child elements we add one event listener to the parent. then the paren handle events for all child.It is useful because it need less code and also saves memory space

5. What is the difference between preventDefault() and stopPropagation() methods?
Ans: 
preventDefault():
1.It stops the default browser action
stopPropagation():
1.It stops the event to move to the parent element 
