---
title: "Introduction of Node.js"
description: "What is Node.js?"
date: "2020-03-02T07:22:19.816Z"
categories: []
published: false
---

### What is Node.js?

Nodejs is an Environment to run the JavaScript outside the browser. Node.js is a program we can use to execute JavaScript on our computers — making it a JavaScript runtime. Node.js is also used for running server-side JavaScript.

### **Why Node.js?**

There are some features of Node.js are

-   **Asynchronous and Event-Driven — **Asynchronous I/O is a form of input/output processing that permits other processing to continue before the transmission has finished.
-   **Very Fast** − Being built on Google Chrome’s V8 JavaScript Engine, Node.js library is very fast in code execution.
-   **Single-Threaded but Highly Scalable — **Node.js is non-blocking which means that all functions ( callbacks ) are delegated to the event loop and they are ( or can be ) executed by different threads. That is handled by Node.js run-time.
-   **No Buffering** − Node.js applications never buffer any data. These applications simply output the data in chunks.

### **Blocking I/O**

In the blocking method, user2’s data request is not initiated until user1’s data is printed to the screen.

If this was a web server, we would have to start a new thread for every new user. But JavaScript is single-threaded (not really, but it has a single-threaded event loop, which we’ll discuss a bit later). So this would make JavaScript not very well suited for multi-threaded tasks.

That’s where the non-blocking part comes in.

### **Non-Blocking I/O**

On the other hand, using a non-blocking request, you can initiate a data request for user2 without waiting for the response to the request for user1. You can initiate both requests in parallel.

This non-blocking I/O eliminates the need for multi-threading since the server can handle multiple requests at the same time.

![source: [http://www.techthali.org/node.js---asynchronous---non-blocking---events---callbacks-/](http://www.techthali.org/node.js---asynchronous---non-blocking---events---callbacks-/)](./asset-1.png)
