# Javascript Tutorial Outline

1.1 An Introduction to JavaScript
1.2 Manuals and specifications
1.3 Code editors
1.4 Developer console

## JavaScript Fundamentals

2.1 Hello, world!
2.2 Code structure
2.3 The modern mode, "use strict"
2.4 Variables
2.5 Data types
2.6 Interaction: alert, prompt, confirm
2.7 Type Conversions
2.8 Basic operators, maths
2.9 Comparisons
2.10 Conditional branching: if, '?'
2.11 Logical operators
2.12 Nullish coalescing operator '??'
2.13 Loops: while and for
2.14 The "switch" statement
2.15 Functions
2.16 Function expressions
2.17 Arrow functions, the basics
2.18 JavaScript specials

## Code quality

3.1 Debugging in the browser
3.2 Coding Style
3.3 Comments
3.4 Ninja code
3.5 Automated testing with Mocha
3.6 Polyfills and transpilers

## Objects: the basics

4.1 Objects
4.2 Object references and copying
4.3 Garbage collection
4.4 Object methods, "this"
4.5 Constructor, operator "new"
4.6 Optional chaining '?.'
4.7 Symbol type
4.8 Object to primitive conversion

## Data types

5.1 Methods of primitives
5.2 Numbers
5.3 Strings
5.4 Arrays
5.5 Array methods
5.6 Iterables
5.7 Map and Set
5.8 WeakMap and WeakSet
5.9 Object.keys, values, entries
5.10 Destructuring assignment
5.11 Date and time
5.12 JSON methods, toJSON

## Advanced working with functions

6.1 Recursion and stack
6.2 Rest parameters and spread syntax
6.3 Variable scope, closure
6.4 The old "var"
6.5 Global object
6.6 Function object, NFE
6.7 The "new Function" syntax
6.8 Scheduling: setTimeout and setInterval
6.8 Decorators and forwarding, call/apply
6.10 Function binding
6.11 Arrow functions revisited

## Object properties configuration

7.1 Property flags and descriptors
7.2 Property getters and setters

## Prototypes, inheritance

8.1 Prototypal inheritance
8.2 F.prototype
8.3 Native prototypes
8.4 Prototype methods, objects without `__proto__`

## Classes

9.1 Class basic syntax
9.2 Class inheritance
9.3 Static properties and methods
9.4 Private and protected properties and methods
9.5 Extending built-in classes
9.6 Class checking: "instanceof"
9.7 Mixins

## Error handling

10.1 Error handling, "try...catch"
10.2 Custom errors, extending Error

## Promises, async/await

11.1 Introduction: callbacks
11.2 Promise
11.3 Promises chaining
11.4 Error handling with promises
11.5 Promise API
11.6 Promisification
11.7 Microtasks
11.8 Async/await

## Generators, advanced iteration

12.1 Generators
12.2 Async iteration and generators

## Modules

13.1 Modules, introduction
13.2 Export and Import
13.3 Dynamic imports

## Miscellaneous

14.1 Proxy and Reflect
14.2 Eval: run a code string
14.3 Currying
14.4 Reference Type
14.5 BigInt
14.6 Unicode, String internals
14.7 WeakRef and FinalizationRegistry

# Browser: Document, Events, Interfaces

Learning how to manage the browser page: add elements, manipulate their size and position, dynamically create interfaces and interact with the visitor.

## Document

1.1 Browser environment, specs
1.2 DOM tree
1.3 Walking the DOM
1.4 Searching: `getElement*`, `querySelector*`
1.5 Node properties: type, tag and contents
1.6 Attributes and properties
1.7 Modifying the document
1.8 Styles and classes
1.9 Element size and scrolling
1.10 Window sizes and scrolling
1.11 Coordinates

## Introduction to Events

2.1 Introduction to browser events
2.2 Bubbling and capturing
2.3 Event delegation
2.4 Browser default actions
2.5 Dispatching custom events

## UI Events

3.1 Mouse events
3.2 Moving the mouse: mouseover/out, mouseenter/leave
3.3 Drag'n'Drop with mouse events
3.4 Pointer events
3.5 Keyboard: keydown and keyup
3.6 Scrolling

## Forms, controls

4.1 Form properties and methods
4.2 Focusing: focus/blur
4.3 Events: change, input, cut, copy, paste
4.4 Forms: event and method submit

## Document and resource loading

5.1 Page: DOMContentLoaded, load, beforeunload, unload
5.2 Scripts: async, defer
5.3 Resource loading: onload and onerror

## Miscellaneous

6.1 Mutation observer
6.2 Selection and Range
6.3 Event loop: microtasks and macrotasks

# Additional articles

List of extra topics that assume you've covered the first two parts of tutorial. There is no clear hierarchy here, you can read articles in the order you want.

## Frames and windows

1.1 Popups and window methods
1.2 Cross-window communication
1.3 The clickjacking attack

## Binary data, files

2.1 ArrayBuffer, binary arrays
2.2 TextDecoder and TextEncoder
2.3 Blob
2.4 File and FileReader

## Network requests

3.1 Fetch
3.2 FormData
3.3 Fetch: Download progress
3.4 Fetch: Abort
3.5 Fetch: Cross-Origin Requests
3.6 Fetch API
3.7 URL objects
3.8 XMLHttpRequest
3.8 Resumable file upload
3.10 Long polling
3.11 WebSocket
3.12 Server Sent Events

## Storing data in the browser

4.1 Cookies, document.cookie
4.2 LocalStorage, sessionStorage
4.3 IndexedDB

## Animation

5.1 Bezier curve
5.2 CSS-animations
5.3 JavaScript animations

## Web components

6.1 From the orbital height
6.2 Custom elements
6.3 Shadow DOM
6.4 Template element
6.5 Shadow DOM slots, composition
6.6 Shadow DOM styling
6.7 Shadow DOM and events

## Regular expressions

7.1 Patterns and flags
7.2 Character classes
7.3 Unicode: flag "u" and class \p{...}
7.4 Anchors: string start ^ and end $
7.5 Multiline mode of anchors ^ $, flag "m"
7.6 Word boundary: \b
7.7 Escaping, special characters
7.8 Sets and ranges [...]
7.9 Quantifiers +, \*, ? and {n}
7.10 Greedy and lazy quantifiers
7.11 Capturing groups
7.12 Backreferences in pattern: \N and \k<name>
7.13 Alternation (OR) |
7.14 Lookahead and lookbehind
7.15 Catastrophic backtracking
7.16 Sticky flag "y", searching at position
7.17 Methods of RegExp and String
