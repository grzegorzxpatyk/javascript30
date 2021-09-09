# JavaScript30

My journal of getting through [__JavaScript30__](https://javascript30.com) challenge by *Wes Bos*.
Notes of what new I've learned in every day. I'm trying to note everything, even most obvious things, that seemed useful when completing the challenge, so I will remember them better.

## Day 01 - Drum Kit
What did I learn?

+ key events in javascript
+ element[attribute="value"] syntax works the same as in css
+ `transitionend` event - gets fired when the transition of the element ends ([docs](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/transitionend_event))

## Day 02 - CSS & JS Clock
New stuff:

+ `transform-origin` and `transition-timing-function` __css__ properties
+ cubic bezier icon in dev tools let you experiment with different timing functions
+ `item.style.transform` can take a _template literal_ string
+ _Date_ class & `getSeconds`, `getMinutes` and `getHours` methods
+ `setInterval(callback function, interval in miliseconds);`

## Day 03 - Update CSS Variables with JS

+ NodeList ≠ Array - lacks of methods that an array have 
+ you can cast NodeList to an Array in JS
+ `this.dataset` returns all _data-_ prefixed attributes of the referenced html element
+ `this.dataset.attribute` returns the value of the particular referenced attribute
+ `element.style.setProperty('propertyName', 'propertyValue')` - accepts template literals!

## Day 04 - Array Cardio Day 1

+ `querySelector` and `querySelectorAll` returns a NodeList instead of an array. NodeList has only `forEach()` method.
+ `Array.prototype.sort()` syntax with ternary operator - `return a > b ? 1 : -1`
+ `Array.prototype.reduce()` method is a good way for counting instances of an element in an array

## Day 05 - Flex Panels Image Gallery

+ creating a multiple EventListeners for each element of the node list with 
````javascript
elements.forEach(element => element.addEventListener('click', function));
````
+  flex box - `flex: value` let's you control the increased/decreased value of a flex element
+ transitionend `propertyName` let's you stack and control the transitions

## Day 06 - Type Ahead

+ fetching data with `fetch()` using promises etc.
+ regular expressions
+ `String.prototype.replace()` with use of innerHTML lets you highlight the matching suggestion in search bar