1. What is React?

Ans:- React is also known as ReactJs or React.js. It is developed by Facebook. It is a free and open source 
      front-end JavaScript library for building user interfaces based on components.
      
      React can be used to develop single-page, mobile, or server-rendered applications with frameworks like Next.js.It aims to allow developers to create fast user interfaces for websites and applications alike easily. The main concept of React.js is virtual DOM.

      (Why we use React) :-
      It is a new standard in javaScript development. It promotes an alternative to the traditional javaScript frameworks approach for data and state management,which makes better performance and clean architecture.
      React allows developers to create reusable UI components that manage their own state, making it easier to build complex UIs.


                *------------- Key Benefits of React JS for Front-end Development -----------------*


     Speed:--

    React basically allows developers to utilize individual parts of their application on both the client-side and the server-side, which ultimately boosts the speed of the development process.

    In simple terms, different developers can write individual parts and all changes made won’t cause the logic of the application.


    Flexibility:--

    Compared to other frontend frameworks, the React code is easier to maintain and is flexible due to its modular structure. This flexibility, in turn, saves a huge amount of time and cost for businesses.


    Performance:--

    React JS was designed to provide high performance in mind. The core of the framework offers a virtual DOM program and server-side rendering, which makes complex apps run extremely fast.

   

    Usability:--

    Deploying React is fairly easy to accomplish if you have some basic knowledge of JavaScript.

    In fact, an expert JavaScript developer can easily learn all the ins and outs of the React framework in a matter of a day or two.


    Reusable Components:--

    One of the main benefits of using React JS is its potential to reuse components. It saves time for developers as they don’t have to write various codes for the same features. Furthermore, if any changes are made in any particular part, it will not affect other parts of the application.


    Mobile app development:--

     React is not only for web development, Facebook has already upgraded the framework for developing mobile native applications for both Android & iOS platforms.

    



                  *--------------Key concepts and features of React include--------------------*


    (Components):- 
     React applications are typically built using components, which are self-contained and reusable pieces of code. Components can represent parts of a user interface, such as buttons, forms, or entire sections of a page.

    JSX (JavaScript XML):- 
     JSX is a syntax extension for JavaScript that looks similar to XML or HTML. It allows developers to write UI components in a syntax that closely resembles the final output, making the code more readable and maintainable.

    (Virtual DOM):-
     React maintains a lightweight in-memory representation of the actual DOM. When the state of a component changes, React first updates the virtual DOM and then efficiently updates the real DOM only where necessary.

    (One-way data binding):-
     React follows a unidirectional data flow, where data changes in a parent component can be passed down to child components through props. This helps maintain a predictable state and makes it easier to understand how data is flowing through the application.

    (React Router):-
     React Router is a popular library used for handling navigation in React applications. It enables the creation of single-page applications with dynamic, client-side routing.



--------------------------------------------------------------------------------------------------------------------




2. Who made React?

Ans:- React was created by Jordan Walke, a software engineer at Facebook. He was inspired by the functional  
      programming language Lisp and sought to create a library that would allow developers to create reusable components that could be easily combined to build complex user interfaces.

      React was initially used to build the Facebook news feed and was later released as an open-source project. It quickly gained traction within the developer community due to its simplicity and flexibility.

      In other words, React was created by Jordan Walke, a software engineer at Meta, who released an early prototype of React called "FaxJS".He was influenced by XHP, an HTML component library for PHP. It was first deployed on Facebook's News Feed in 2011 and later on Instagram in 2012. It was open-sourced at JSConf US in May 2013.

      React Native, which enables native Android, iOS, and UWP development with React, was announced at Facebook's React Conf in February 2015 and open-sourced in March 2015.



    Why React is created:-

      Back in 2011, Facebook had a massive user base and faced a challenging task. It wanted to offer users a richer user experience by building a more dynamic and more responsive user interface that was fast and highly performant. Jordan Walke, one of Facebook's software engineers, created React to do just that.

      React was created to address specific challenges and needs that developers faced while building user interfaces for complex web applications, particularly within Facebook.


      
    React native:-

      When Facebook announced the creation of React Native, spearheaded by a team of its engineers including Christopher Chedeau, Jordan Walke, Ashwin Bharambe, and Lin He., they had in mind to build an efficient framework that would result in reduced development costs as well as deliver consistent user experience. This was done with the idea that JavaScript code could be compiled into multiple platforms, allowing for quicker iterations and releasing native mobile apps onto app stores much faster than before.




    Why is it called ReactJS?

      The name “React” reflects this reactive nature of the library. The idea behind React is to build reusable components that can be rendered on the front-end, rather than writing a new piece of code every time you need to display something on the screen.


--------------------------------------------------------------------------------------------------------------------


3. What is Babel?

Ans:- Babel is a JavaScript compiler.
      Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments.

      If we want, we can also optionally use it to transpile TypeScript into regular JavaScript that will run in a browser. It’s also used for JSX.

      Here are the main things Babel can do:-

      Transform syntax.
      Polyfill features that are missing in your target environment (through a third-party polyfill such as core-js).
      Source code transformations (codemods).


      ----------Why Babel is important in React ------------

      Babel is an important tool in the React ecosystem for several reasons. Here are some key points to consider:

    Compatibility:-
       React uses contemporary JavaScript syntax, which is incompatible with older browsers. Babel React enables developers to write React code in the most recent syntax, which is subsequently compiled into JavaScript that can be run by older browsers. This implies that developers can use the most recent JavaScript capabilities without fear of browser compatibility difficulties.


    JSX syntax:-
       JSX is a JavaScript syntactic extension that lets you write HTML-like syntax in JavaScript. React components are written in JSX, which is not supported by older browsers. Babel allows developers to use JSX syntax and compiles it into JavaScript that older browsers can run. Babel features a preset named babel-preset-react that includes all of the plugins required to convert JSX syntax to standard JavaScript.

    Flexibility:-
        Babel isn’t just for React JS; it can be used with any JavaScript project. It contains a large ecosystem of plugins that may be used to change certain JavaScript features. Babel allows developers to build more efficient and maintainable code while maintaining browser compatibility.


                          *********************** Babel and JSX **************************

        JSX is a JavaScript syntax extension that allows developers to construct HTML-like syntax in their JavaScript code. Writing React components using JSX makes it easy to develop complicated user interfaces. JSX, on the other hand, is incompatible with older browsers, which is where Babel for React comes in.

        Babel has a preset called babel-preset-react that contains all of the plugins needed to convert JSX syntax into normal JavaScript. When developers create code in JSX syntax, Babel transforms it into JavaScript, which older browsers can run. This implies that developers can write React components using JSX syntax without worrying about browser compatibility issues.

        Babel also allows developers to use the latest features of JavaScript, including ES6+ syntax, when writing React components. This contemporary syntax is converted by Babel into a kind of JavaScript that may be used with older browsers. By using Babel with React, developers can write efficient and maintainable code without compromising browser compatibility.

 

 -------------------------------------------------------------------------------------------------------------------



4. How does Babel convert html code in React into valid code?

Ans:- Babel is a key tool that can translate JSX syntax, which is used to create HTML-like code in React 
      components, into valid JavaScript code that can be executed in preferred browsers. By converting the JSX code into JavaScript functions that return the same HTML-like structures.

      To convert HTML code to React, you need to break down the HTML code into smaller React components.

      Here are the basic steps to convert:-

      1. Identify the repetitive or reusable parts of the HTML code and create a React component for them. This will help you to manage the code better by having smaller chunks that can be easily maintained.

      2. Convert the remaining HTML into JSX. JSX is similar to HTML, but it allows you to write JavaScript code within it.

      3. Replace the HTML tags with the equivalent JSX tags. For example, replace the class attribute with the className attribute and the for attribute with the htmlFor attribute.

      4. Add the appropriate React syntax, such as props, state, and lifecycle methods to create a working React component.

Here is an example to convert an HTML code to React:

HTML Code:-


<div class="container">
  <h1>Hello World!</h1>
  <p>Hello React.</p>
</div>


React Code:-

function Container() {
  return (
    <div className="container">
      <h1>Hello World!</h1>
      <p>Hello React.</p>
    </div>
  );
}



--------------------------------------------------------------------------------------------------------------------




5. What is ReactDOM used for? Write an example?

Ans:- ReactDOM is a package in React that provides DOM-specific methods that can be used at the top level of a web 
      app to enable an efficient way of managing DOM elements of the web page. ReactDOM provides the developers with  an API containing the various methods to manipulate DOM.


Example:-

// Import necessary modules from React
    import React from 'react';
    import ReactDOM from 'react-dom';

// Define a React component
    const MyComponent = () => {
    return <h1>Hello, React!</h1>;
   };

// Get a reference to the root DOM element where you want to render your React component
    const rootElement = document.getElementById('root');

// Use ReactDOM to render the React component into the specified DOM element
    ReactDOM.render(<MyComponent />, rootElement);


The react-dom package also provides modules specific to client and server apps:-

    react-dom/client.
    react-dom/server.


The react-dom package exports these methods:

    createPortal()
    flushSync()


These react-dom methods are also exported, but are considered legacy:

    render()
    hydrate()
    findDOMNode()
    unmountComponentAtNode()



--------------------------------------------------------------------------------------------------------------------





6. What are the packages that you need to import for react to work with?

Ans:- To work with React, we  need to import a few essential packages and libraries.

   Here are the primary ones:-

    (1).React:
    import React from 'react';

    (2).React DOM:
    import ReactDOM from 'react-dom';
    This library is used for rendering React components in the browser.

    (3).JSX (JavaScript XML):
    JSX allows you to write HTML elements and components in a syntax similar to XML or HTML in your JavaScript code. Babel is commonly used to transpile JSX into JavaScript.

    No need for a separate import; JSX is usually included in your JavaScript files.

    (4).Component Definition:
    // For creating React components
    import React, { Component } from 'react';
    If you are using functional components, you can omit the { Component } part.

    (5).Props:
    // For handling component properties
    import PropTypes from 'prop-types';
    This package is used for defining the types of props that a component should receive.

    (6).State:
    // For managing component state
    import { useState } from 'react';
    If you are using class components, state is managed using the this.state and this.setState methods.

    (7).Effect Hooks:
    // For handling side effects in functional components
    import { useEffect } from 'react';
    This is used to perform side effects in functional components, such as data fetching, subscriptions, or manually changing the DOM.

    (8).Router (for React Router, if you're building a single-page application):
    // For handling navigation in a React application
    import { BrowserRouter as Router, Route, Switch } from 'react-router-dom';
    This is commonly used for client-side routing.

    (9).Redux (if you're using Redux for state management):
    import { createStore } from 'redux';
    import { Provider } from 'react-redux';
    Redux is not mandatory for all React applications, but it's commonly used for managing global state.

   (10).Axios or Fetch (for making HTTP requests):
   // Axios is a popular library for making HTTP requests
   import axios from 'axios';
   // Or use the built-in Fetch API
   We can choose either Axios or the Fetch API for handling HTTP requests.

Remember that the specific packages we need may vary depending on your project's requirements. Additionally, it's crucial to have Node.js and npm (Node Package Manager) installed to manage and install these packages. we can initialize a new React project using tools like Create React App or set up your own project structure.




--------------------------------------------------------------------------------------------------------------------





7. How do you add react to a web application?

Ans:- To add react to an web application we follow these steps :-

    Step 1: Add a DOM Container to the HTML:-

            First, open the HTML page you want to edit. Add an empty <div> tag to mark the spot where we want to display something with React. 
     For example:

   <!-- ... existing HTML ... -->

   <div id="like_button_container"></div>

   <!-- ... existing HTML ... -->
        We gave this <div> a unique id HTML attribute. This will allow us to find it from the JavaScript code later and display a React component inside of it.

    Step 2: Add the Script Tags:-

        Next, we add three <script> tags to the HTML page right before the closing </body> tag:-

   <!-- ... other HTML ... -->

   <!-- Load React. -->
   <!-- Note: when deploying, replace "development.js" with "production.min.js". -->
   <script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin></script>
   <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin></script>

   <!-- Load our React component. -->
   <script src="like_button.js"></script>

 </body>
   The first two tags load React. The third one will load our component code.


Step 3: Create a React Component:-

    Then next we create a file called like_button.js next to our HTML page.
    Open this starter code and paste it into the file we created.

    After the starter code, add three lines to the bottom of like_button.js:


// ... the starter code we have to paste here...

 const domContainer = document.querySelector('#like_button_container');
 const root = ReactDOM.createRoot(domContainer);
 root.render(e(LikeButton));

 These three lines of code find the <div> we added to our HTML in the first step, create a React app with it, and then display our “Like” button React component inside of it.




--------------------------------------------------------------------------------------------------------------------



    

8. What is React.createElement?

Ans:- React.createElement is a fundamental method of React JS. The main use of React.createElement is the Creation 
      of a React component. It is the JavaScript format for creating react components. Also, the JSX react component when transpired invokes this only method for creating the component.

 Syntax:
   React.createElement(type,{props},children); 
   // JSX code 
 <type {props} >{children}</type


   Parameters: React.createElement() takes three arguments. They are:-

   type:- the type of the HTML element (h1,p, button, etc).
   props:- properties of the object({style:{size:10px}} or Eventhandlers, classNames,etc).
   children:- anything that needs to be enclosed by that component.


   React DOM:- 
             React DOM contains the arguments that are necessary to render react elements in the browser.

   ReactDOM.render(element,containerElement);

   Parameters: ReactDOM.render() takes two arguments:-

   element:- The element that needs to be rendered in the DOM.
   containerElement:- Where to render in the dom.




--------------------------------------------------------------------------------------------------------------------




9. What are the three properties that createElement accept?

Ans:- The React.createElement() function takes three arguments:-
      (i) type
      (ii) props
      (iii) children.
      And returns an object just like the one above.

Ex:-   React.createElement(type, props, children)

    CreateElement lets us create a React element. It serves as an alternative to writing JSX.

    const element = createElement(type, props, ...children)

    Reference:
    createElement(type, props, ...children)

    Usage:
    Creating an element without JSX.


Here is an example:-

Call createElement to create a React element with the given type, props, and children.

import { createElement } from 'react';

function Greeting({ name }) {
  return createElement(
    'h1',
    { className: 'greeting' },
    'Hello'
  );
}


PARAMETERS:-

type:-
     The type argument must be a valid React component type. For example, it could be a tag name string (such as 'div' or 'span'), or a React component (a function, a class, or a special component like Fragment).

props:-
      The props argument must either be an object or null. If you pass null, it will be treated the same as an empty object. React will create an element with props matching the props you have passed. Note that ref and key from your props object are special and will not be available as element.props.ref and element.props.key on the returned element. They will be available as element.ref and element.key.

optional (...children):-
       Zero or more child nodes. They can be any React nodes, including React elements, strings, numbers, portals, empty nodes (null, undefined, true, and false), and arrays of React nodes.



Returns :-
createElement returns a React element object with a few properties:-

type:- The type we have passed.

props:- The props we have passed except for ref and key. If the type is a component with legacy type.defaultProps, 
        then any missing or undefined props will get the values from type.defaultProps.

ref:- The ref we have passed. If missing, null.

key:- The key we have passed, coerced to a string. If missing, null.





--------------------------------------------------------------------------------------------------------------------





10. What is the meaning of render and root?

Ans:- Render:-
      Render in React JS is a fundamental part of class components. It is used to display the component on the UI returned as HTML or JSX components. The ReactDOM.render() function takes two arguments, HTML code and an HTML element.

      In other words,The root is where the application layout structure is defined. It is typically the first UI element a user interacts with. The root can be changed multiple times during the lifespan of the application.


 Main purpose of render():-

    a.  React renders HTML to the web page by using a function called render().
    b.  The purpose of the function is to display the specified HTML code inside the specified HTML element.
    c.  In the render() method, we can read props and state and return our JSX code to the root component of our   
        app.
    d.  In the render() method, we cannot change the state, and we cannot cause side effects( such as making an  
        HTTP request to the webserver).


     Root:-
     In React, the root element refers to the top-level element that is the parent of all other components in our application.

     It is typically represented as a DOM node within the public/index.html file that serves as the entry point for our React app.


     For example, in the following code, root is a DOM node that serves as the starting point for rendering our React components:


  import React from 'react';
  import ReactDOM from 'react-dom';

 const App = () => {
  return (
    <div>
      <h1>Hello, World!</h1>
    </div>
   );
  };

    ReactDOM.render(<App />, document.getElementById('root'));
    Here, the ReactDOM.render() method is used to render the App component inside the root element, which is referenced by document.getElementById('root').