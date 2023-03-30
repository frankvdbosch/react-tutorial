# Public folder

This folder consists of all the files that are public to the browser.

# React.StrictMode

This wrapper in index.js does additional che=cks during developnent and it gives us warning down in the console.

# Package.json

Lists all the dependencies of the application. It also lists the scripts you can use in your application.

# npm install

Looks inside your package.json and installs all the dependencies that are listed there.

# Babel

In the background a transpiler called Babel converts the jsx code to html when we save a file. And it renders the html to the DOM.

# import React from "react";

Not needed in app.js anymore, except in react versions older than 17.

# div.content

Creates a <div className="content"></div>

# Inject dynamic fiels in the DOM

{const_name}. Works with every data type, except booleans and objects.
(math.random() \* 10) also works
Also works on dynamic attributes: <a href={link}>Google site</a>

# Stateless functional component

Type "sfc" to make a stateless functional component. It's a good starting point for a component.

# React hook

A hook is a special type of function that does a certain kind of job. A hook's name always start with "use". For example "useState".

# useState

The useState function allows us to change a value within our component.js and let React render that value to a DOM element when a event happens, such as a mouse click. A hook function return two value. The first one is the value and the second one is the function that we can use to change that value and rerender the component.js.n You create "state" when you expect things to be changed in de the DOM. Changing multiple items at once will be done with an array intead of a single value.

# looping through an array

To avoid using repetitive code, you loop through an array of values to render them to the DOM by using the .map() method of an array.

# using props

We use props to pass data from one component (a parent component) to another component (a child component). This is a bit like passing a parameter to a function. You can also pass functions as props, for example a delete function from a parent component to a child component.

# useEffect hook

With this function you can run code at every render of the DOM. This could for example be a function. It is very often used to fetch (external) data the first time te DOM renders. For example, a database using an API endpoint. From then, you can us this data during the next render of certain components in de the DOM.

# useEffect dependencies

You can set dependencies upon which the useEffect hook is triggered, so that it only runs when a specific state changes instead of every render of the DOM.

# JSON server package

This package allows us to built a fake REST API by just using a json file. Link to tutorial JSON server: https://www.youtube.com/watch?v=mAqYJF-yxO8&list=PL4cUxeGkcC9i2v2ZqJgydXIcRq_ZizIdD&index=1&t=0s
You can run json-server from the web instead of locally to watch your local json file by running this command: npm json-server --watch data/db.json --port 8000
This command installs the package first.

# custom hooks

You can also make a custom hook by making a file with a name that starts with "use", for example "useFetch" to fetch data from a database on another server.

# react router package

This package allow to route the user to different pages.
With this command you can install this package: npm install react-router-dom

# switch

In the <Switch> component the different routes are defined.

# useHistory hook

This hook allow you to go back and forward through the history. In other words: redirect the user to a new route.
