# javascript-handbook

A guide for terms and concepts that are helpful to know if you're a javascript developer.

## Table of Contents
- [Client-side](#client-side)
  - [dom](#dom)
  - [event](#event)
  - [event delegation](#event-delegation)
  - [event listener](#event-listener)
  - [selector](#selector)
- [General](#general)
  - [asynchronous](#asynchronous)
  - [closure](#closure)
  - [equality (triple vs. double equal)](#equality)
  - [event loop](#event-loop)
  - [hoisting](#hoisting)
- [Server-side](#server-side)
  - [bower](#bower)
  - [event-driven](#event-driven)
  - [grunt](#grunt)
  - [node.js](#nodejs)
  - [npm](#npm)

## Client-side

### dom
An API to access the elements within an HTML or XML document.

### event
The performing of certain actions on a web page.

### event delegation
Avoiding adding an event listener to multiple elements, instead, adding it to a parent element and analyzing the bubbled event there.

### event listener
A notifier when an event on an element occurs.

### selector
A pattern used to select HTML elements.

## General

### asynchronous
A form of processing that does not block other processes during execution.

### closure
The behaviour of functions to maintain it's parent scope - even after the parent scope is destroyed.

### equality
`===`: compares two values for equality

`==`: converts values to a common type then compares for equality

### event loop
An entity that controls and dispatches events following an initial event.

### hoisting
The behaviour of variable declarations to be moved to the top.

## Server-side

### bower
A package manager for web components.

### event-driven
A programming paradigm where the flow of the program is determined by events.

### grunt
A task runner for node.js.

### node.js
A platform built on Chrome's V8 JavaScript engine for building network applications.

### npm
A package manager for node.js modules.
