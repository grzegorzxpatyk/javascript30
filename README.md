# JavaScript30

My journal of getting through [**JavaScript30**](https://javascript30.com) challenge by _Wes Bos_.
Notes of what new I've learned in every day. I'm trying to note everything, even most obvious things, that seemed useful when completing the challenge, so I will remember them better.

## Day 01 - Drum Kit

What did I learn?

-   key events in javascript
-   element[attribute="value"] syntax works the same as in css
-   `transitionend` event - gets fired when the transition of the element ends ([docs](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/transitionend_event))

## Day 02 - CSS & JS Clock

New stuff:

-   `transform-origin` and `transition-timing-function` **css** properties
-   cubic bezier icon in dev tools let you experiment with different timing functions
-   `item.style.transform` can take a _template literal_ string
-   _Date_ class & `getSeconds`, `getMinutes` and `getHours` methods
-   `setInterval(callback function, interval in miliseconds);`

## Day 03 - Update CSS Variables with JS

-   NodeList ≠ Array - lacks of methods that an array have
-   you can cast NodeList to an Array in JS
-   `this.dataset` returns all _data-_ prefixed attributes of the referenced html element
-   `this.dataset.attribute` returns the value of the particular referenced attribute
-   `element.style.setProperty('propertyName', 'propertyValue')` - accepts template literals!

## Day 04 - Array Cardio Day 1

-   `querySelector` and `querySelectorAll` returns a NodeList instead of an array. NodeList has only `forEach()` method.
-   `Array.prototype.sort()` syntax with ternary operator - `return a > b ? 1 : -1`
-   `Array.prototype.reduce()` method is a good way for counting instances of an element in an array

## Day 05 - Flex Panels Image Gallery

-   creating a multiple EventListeners for each element of the node list with

```javascript
elements.forEach(element => element.addEventListener('click', function));
```

-   flex box - `flex: value` let's you control the increased/decreased value of a flex element
-   transitionend `propertyName` let's you stack and control the transitions

## Day 06 - Type Ahead

-   fetching data with `fetch()` using promises etc.
-   regular expressions
-   `String.prototype.replace()` with use of innerHTML lets you highlight the matching suggestion in search bar

## Day 07 - Array Cardio Day 2

-   Spread operator in arrays:

```javascript
const newComments = [
    ...comments.slice(0, index), // the spread operator
    ...comments.slice(index + 1),
];
```

-   `console.table();`
-   repetition of the methods:

```javascript
Array.prototype.some();
Array.prototype.every();
Array.prototype.find();
Array.prototype.findIndex();
```

## Day 08 - HTML5 Canvas

-   Learn how to set HTML5 Canvas
-   Mouse events:

```javascript
mousedown / mouseup;
mouseover / mouseout;
mousemove;
```

-   Canvas context properties:

```javascript
.lineWidth
.lineCap
.lineJoin
.strokeStyle
```

## Day 09 - 14 Must Know Dev Tools Tricks

-   `console.log()`
-   `console.log('%c That\'s going to be a styled string', 'some styling in css')`
-   `console.warn('Warning message!')`
-   `console.error('Error message!')`
-   `console.info('Some fun fact.')`
-   `console.assert(condition, that what happens when the condition is false)`
-   `console.clear()`
-   `console.dir(element)`
-   `console.group()` and `console.groupCollapse()`
-   `console.count()`
-   `console.time()` and `console.timeEnd()`
-   `console.table()`

## Day 10 - Hold Shift and Check Checkboxes

-   Got to know the `this` keyword a little much better, and recalled the difference between function declaration and function expression.
-   Also the dug into the difference between `event.target` property and `event.currentTarget`.
-   `event` object has a `shiftKey` property - didn't know that!
