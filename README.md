Question:1
What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Answer:1
getElementById("id") selects one element by ID

getElementsByClassName("class") selects all elements with that class and returns an HTMLCollection

querySelector("selector") selects the first element that matches a CSS selector

querySelectorAll("selector") selects all elements that match a CSS selector and returns a NodeList

Question:2
 How do you create and insert a new element into the DOM?

Answer:2
first create the element using document.createElement("tag")

then add content if needed like element.textContent = "text"

finally insert it using parent.appendChild(element) or parent.insertBefore(element, reference)

Question:3
What is Event Bubbling? And how does it work?

Answer:3
Event Bubbling is when an event starts from the inner element and moves up to its parent elements.
For example, if you click a button inside a div, first the button handles it, then the div, then the body, and so on

Question:4
What is Event Delegation in JavaScript? Why is it useful?

Answer:4
Event Delegation is when you add an event listener to a parent element instead of each child, and check which child triggered it.
It’s useful because it uses less code and also works for elements added dynamically later

Question:5
What is the difference between preventDefault() and stopPropagation() methods?

Answer:5
The difference between preventDefault() and stopPropagation() is:
preventDefault() stops the browser’s default action like submitting a form or following a link
stopPropagation() stops the event from bubbling up to parent elements