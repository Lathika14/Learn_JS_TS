# JavaScript

## What is JavaScript?

JavaScript is a lightweight, interpreted, object-based scripting
language used to create dynamic and interactive web pages.

It is often called the **"language of the web"** because it is a core
technology used to create dynamic and interactive web applications and
is a fundamental component of front-end web development.

------------------------------------------------------------------------

## Key Features of JavaScript

-   **Interpreted programming language**
-   **Lightweight**
-   **Object-oriented** --- prototype-based
-   Supports **front-end and back-end development**
-   Supports **client-side and server-side validation**
-   **Event-driven architecture**
-   **Asynchronous programming**
-   **Single-threaded with non-blocking I/O**
-   Can be executed outside the browser using **Node.js**
-   Uses browser-specific JavaScript engines such as **V8** in Chrome

------------------------------------------------------------------------

## Why JavaScript is Used

JavaScript allows web pages to respond to user actions such as:

-   Clicking buttons
-   Typing into forms
-   Selecting options
-   Navigating between pages
-   Submitting forms

It can perform these actions dynamically without requiring the entire
page to reload.

### Simple Example

``` javascript
document.getElementById("myButton").addEventListener("click", function() {
    alert("Button clicked!");
});
```

Here, JavaScript waits for the `click` event on `myButton` and executes
the function when the button is clicked.

------------------------------------------------------------------------

## Why JavaScript?

JavaScript is widely used because:

-   It is natively supported by modern web browsers.
-   It can be used for front-end development.
-   It can also run on the server using Node.js.
-   It can therefore be used as part of a **full-stack development**
    solution.
-   It supports interactive and dynamic web applications.

------------------------------------------------------------------------

## JavaScript in Test Automation

JavaScript is used in test automation to:

-   Create automated test scripts
-   Execute automated tests
-   Interact with web applications
-   Build modern test automation frameworks

Popular JavaScript-based automation tools include:

-   Playwright
-   Cypress
-   WebdriverIO

------------------------------------------------------------------------

# History of JavaScript

## Origin --- 1995

JavaScript was created by **Brendan Eich** at Netscape.

Initially, it was called:

1.  Mocha
2.  LiveScript
3.  JavaScript

The name JavaScript was chosen partly to align with the popularity of
Java at that time, although **JavaScript and Java are different
programming languages**.

### Purpose

JavaScript was designed to add interactivity to static HTML pages,
making web applications more dynamic and engaging.

------------------------------------------------------------------------

## Standardization --- 1997

To improve compatibility across browsers, JavaScript was submitted to
**ECMA International**.

This resulted in the first standardized version:

**ECMAScript 1 (ES1)**

> JavaScript is the language, while ECMAScript is the standardized
> specification that defines the language.

------------------------------------------------------------------------

# Modern JavaScript

JavaScript has evolved significantly over the years.

## ES6 --- 2015

ES6 introduced many important features, including:

-   `let`
-   `const`
-   Classes
-   Arrow functions
-   Modules
-   Template literals
-   Destructuring
-   Promises

These features made JavaScript more powerful and easier to use for
modern application development.

## ES8 --- 2017

ES8 introduced:

-   `async`
-   `await`

These features made asynchronous programming easier to write and
understand.

------------------------------------------------------------------------

# Evolution of JavaScript

## Early Days --- 1995

JavaScript was initially used for simple client-side tasks such as:

-   Form validation
-   Checking user input
-   Basic browser interactions

## Enhanced Browser Support --- 1997--2005

As browsers evolved, JavaScript gained more features and became an
important technology for creating interactive web pages.

## AJAX Revolution --- Around 2005

AJAX (**Asynchronous JavaScript and XML**) allowed JavaScript to
communicate with a server and retrieve data without requiring a complete
page reload.

This helped create more dynamic and responsive web applications.

## Node.js --- 2009

Ryan Dahl introduced **Node.js**, which enabled JavaScript to run
outside the browser.

This allowed JavaScript to be used for:

-   Server-side development
-   Backend applications
-   APIs
-   Command-line applications
-   Full-stack development

> **Note:** Outside the browser, Node.js provides a runtime environment
> for executing JavaScript on servers and in backend applications.

------------------------------------------------------------------------

# JavaScript and HTML/CSS

A simple way to understand the three technologies:

### HTML

HTML defines the **structure/content** of a web page.

Example:

``` html
<h1>Login Page</h1>
<button>Login</button>
```

### CSS

CSS controls the **appearance and styling** of the page.

For example:

-   Colors
-   Fonts
-   Size
-   Layout
-   Spacing

### JavaScript

JavaScript adds **behavior and interactivity**.

For example:

-   Button click
-   Form validation
-   Dynamic content
-   API calls
-   Showing/hiding elements

### Simple Analogy

Think of a car:

-   **HTML** → Structure/body of the car
-   **CSS** → Color and appearance
-   **JavaScript** → Logic/behavior that makes it interactive

------------------------------------------------------------------------

# Client-Side and Server-Side JavaScript

## Client-Side JavaScript

Client-side JavaScript runs in the user's browser.

Example:

A login page can use JavaScript to check whether:

-   Username is empty
-   Password is empty
-   Password has the required length

This is called **client-side validation**.

## Server-Side JavaScript

JavaScript can also run on the server using **Node.js**.

For example, during login:

``` text
User enters username/password
        ↓
JavaScript sends request
        ↓
Node.js backend receives request
        ↓
Backend checks database
        ↓
Response is sent back to browser
```

Node.js can communicate with databases and perform backend operations.

> Client-side validation improves user experience, but server-side
> validation is still required for security and data integrity.

------------------------------------------------------------------------

# Browser Engine

A **browser engine** is a core component responsible for processing and
rendering web content.

Examples include:

-   **Blink** --- used by Chrome and other Chromium-based browsers
-   **Gecko** --- used by Firefox
-   **WebKit** --- used by Safari

The browser processes:

-   HTML
-   CSS
-   JavaScript
-   Other web resources

------------------------------------------------------------------------

# JavaScript Engine

A **JavaScript engine** is responsible for executing JavaScript code.

Examples:

  Browser   JavaScript Engine
  --------- -------------------
  Chrome    V8
  Firefox   SpiderMonkey
  Safari    JavaScriptCore
  Edge      V8

### Important

The JavaScript engine is part of the browser's overall execution
environment.

For example:

``` text
Chrome
 ├── Blink → browser rendering engine
 └── V8 → JavaScript engine
```

------------------------------------------------------------------------

# Node.js

Node.js allows JavaScript to run **outside the browser**.

``` text
Browser
   ↓
JavaScript Engine
   ↓
Execute JavaScript
```

For backend applications:

``` text
Server
   ↓
Node.js
   ↓
V8 JavaScript Engine
   ↓
Execute JavaScript
```

Node.js is commonly used for:

-   Backend development
-   REST APIs
-   Web servers
-   Real-time applications
-   Command-line tools

------------------------------------------------------------------------

# Foundation of JavaScript

Important concepts behind JavaScript execution include:

1.  Asynchronous Programming
2.  Event-Driven Architecture
3.  Single-Threaded Execution
4.  Non-Blocking I/O
5.  Event Loop

------------------------------------------------------------------------

# 1. Asynchronous Programming

Asynchronous programming allows a task to start without making the
program wait for that task to finish before continuing with other work.

For example:

``` text
Start
  ↓
Request data from server
  ↓
Continue doing other work
  ↓
Server response arrives
  ↓
Process the response
```

JavaScript commonly uses:

-   Callbacks
-   Promises
-   `async/await`

### Synchronous vs Asynchronous

**Synchronous:**

``` text
Task 1 → finish
           ↓
Task 2 → finish
           ↓
Task 3 → finish
```

**Asynchronous:**

``` text
Task 1 starts
Task 2 can continue
Task 3 can continue
Task 1 result is handled when ready
```

> Note: Asynchronous does not literally mean that JavaScript executes
> multiple JavaScript statements simultaneously on multiple threads.
> JavaScript execution itself is generally single-threaded, while
> asynchronous operations are coordinated through the runtime and event
> loop.

------------------------------------------------------------------------

# 2. Event-Driven Architecture

Event-driven architecture means the program responds to events.

Examples of events:

-   Click
-   Key press
-   Mouse movement
-   Network response
-   Timer completion
-   File operation completion

### Example

``` javascript
document.getElementById("myButton").addEventListener("click", function() {
    alert("Button clicked!");
});
```

Here:

1.  JavaScript selects the button.
2.  `addEventListener()` waits for a `click`.
3.  The user clicks the button.
4.  The callback function executes.
5.  An alert is displayed.

------------------------------------------------------------------------

# 3. Single-Threaded JavaScript

JavaScript is generally **single-threaded**, meaning its main JavaScript
execution uses one call stack.

For example:

``` text
Task 1
  ↓
Task 2
  ↓
Task 3
```

JavaScript does not normally execute multiple pieces of JavaScript code
simultaneously on the main thread.

However, the surrounding runtime can provide mechanisms for handling
asynchronous operations.

------------------------------------------------------------------------

# 4. Non-Blocking I/O

I/O means **Input/Output**.

Examples:

-   Reading files
-   Network requests
-   Database operations
-   API calls

With non-blocking I/O, JavaScript does not have to stop the entire
program while waiting for an I/O operation to complete.

Example:

``` text
JavaScript
   ↓
Send database request
   ↓
Continue other work
   ↓
Database response arrives
   ↓
Callback / Promise handles result
```

This is especially important in Node.js applications.

------------------------------------------------------------------------

# 5. Event Loop

The **event loop** helps JavaScript handle asynchronous operations while
using a single main JavaScript thread.

Simplified flow:

``` text
Call Stack
    ↓
JavaScript executes
    ↓
Async operation starts
    ↓
Runtime handles the operation
    ↓
Operation completes
    ↓
Callback / Promise continuation waits in a queue
    ↓
Event Loop
    ↓
Call Stack becomes available
    ↓
Callback executes
```

The event loop continuously checks whether JavaScript can process
pending tasks.

------------------------------------------------------------------------

# Interpreter

An **interpreter** is a mechanism that reads, translates, and executes
source code at runtime.

A simplified traditional model is:

``` text
Source Code
    ↓
Interpreter
    ↓
Execution
```

### Why is it used?

-   Easy development
-   Quick feedback
-   No separate manual compilation step in the traditional workflow
-   Convenient for scripting

### Important Note

Modern JavaScript engines are more advanced than a simple line-by-line
interpreter. They use multiple execution techniques, including **JIT
(Just-In-Time) compilation** and optimization.

------------------------------------------------------------------------

# JIT --- Just-In-Time Compilation

**JIT compilation** compiles code during runtime and can convert
frequently executed code into optimized machine code.

Simplified flow:

``` text
JavaScript Code
      ↓
JavaScript Engine
      ↓
Runtime Analysis
      ↓
JIT Compilation
      ↓
Optimized Machine Code
      ↓
Execution
```

### Why is JIT used?

JIT compilation can improve performance by optimizing frequently
executed code.

### Problem it helps solve

Pure interpretation can be slower for code that executes repeatedly.

JIT can identify **hot code paths** and optimize them for faster
execution.

------------------------------------------------------------------------

# Interpreter vs JIT Compiler

  -----------------------------------------------------------------------
  Interpreter                         JIT Compiler
  ----------------------------------- -----------------------------------
  Executes code through runtime       Compiles code during runtime
  interpretation                      

  Traditionally associated with       Can generate optimized machine code
  simpler execution                   

  May have lower performance for      Can improve performance for
  repeated execution                  frequently executed code

  Provides runtime execution          Performs runtime optimization

  Simple conceptual model             More complex execution model
  -----------------------------------------------------------------------

> Modern JavaScript engines do not simply use an interpreter or simply
> use a JIT compiler. They combine multiple techniques to achieve good
> startup time and performance.

------------------------------------------------------------------------

# Quick Revision

## JavaScript in One View

``` text
JavaScript
│
├── Lightweight
├── Object-oriented
│   └── Prototype-based
├── Interpreted + JIT optimized
├── Event-driven
├── Asynchronous
├── Single-threaded
├── Non-blocking I/O
│
├── Browser
│   └── JavaScript Engine
│       ├── Chrome → V8
│       ├── Firefox → SpiderMonkey
│       └── Safari → JavaScriptCore
│
└── Outside Browser
    └── Node.js
        └── V8 Engine
```

## Important Terms

  -----------------------------------------------------------------------
  Term                                Simple Meaning
  ----------------------------------- -----------------------------------
  JavaScript                          Programming language used to create
                                      dynamic applications

  ECMAScript                          Standard/specification for
                                      JavaScript

  Browser                             Environment where web applications
                                      run

  JavaScript Engine                   Executes JavaScript code

  Node.js                             Runtime environment for running
                                      JavaScript outside the browser

  Event                               Something that happens, such as a
                                      click

  Event Listener                      Code that waits for an event

  Event Loop                          Coordinates asynchronous
                                      callbacks/tasks

  Asynchronous                        Allows operations to proceed
                                      without waiting synchronously

  Non-blocking I/O                    I/O operations do not block the
                                      main JavaScript execution

  JIT                                 Runtime compilation and
                                      optimization

  V8                                  JavaScript engine used by Chrome
                                      and Node.js
  -----------------------------------------------------------------------
