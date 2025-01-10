---
title: Errorhandling in React
description: 3 types of errors and how to handle them in a React application
layout: default
nav_order: 14
parent: React
grand_parent: Toolbox
has_children: false
permalink: /toolbox/react/error-handling
---

# Error handling in a React application

There are many types of errors that can occur in a React application.
These errors can be caused by a variety of factors, such as bugs in the code, network issues,
or problems with the rendering process.

- In this [React error demo](https://github.com/dat3Cph/errorhandling-in-react)

we will demonstrate different types of errors that can occur in a React application
and how to handle them.

## 4 main types of errors

1. **JS runtime errors**: These are errors that occur when the code is running. These are the most common type of errors and are usually caused by a mistake in the code, type errors, etc.

2. **Network errors**: These are errors that occur when the application is trying to communicate with a server. These errors are usually caused by a problem with the network connection. Often you will handle these errors with a `try...catch` statement.

3. **React render errors**: These are errors that occur when the React application is rendering. These errors are usually caused by a problem with the React code. Missing props, undefined variables, etc.

4. **Routing errors**: These are errors that occur when the application is trying to navigate to a different page. These errors are usually caused by a problem with the routing configuration. Missing routes, incorrect paths, etc.

Try to clone and run the demo to see how the different types of errors are handled in a React application.

There will also be more information on how to handle these errors in the Readme file of the demo.
