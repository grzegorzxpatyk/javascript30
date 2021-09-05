# JavaScript30

My jorunal of getting through __JavaScript30__ challenge by *Wes Bos*.
Notes of what new I've learned in every day.

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
