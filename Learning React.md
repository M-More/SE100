# Learning React

![react-logo](https://static.oschina.net/uploads/space/2016/0912/074134_YtbD_2903254.png)

### What is React?
* A JavaScript library for building user interfaces
* Many people choose to think of React as the **'V'** in **MVC**
* Maintained by Facebook and a community of individual developers and companies
* First deployed on Facebook's newsfeed in 2011, Open-sourced in May 2013
***

### Why React?
#### Simple
React has quite a small API. This makes it fun to use, easy to learn, and simple to understand.
#### Declarative
React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes.
Declarative views make your code more predictable and easier to debug.
#### Component-Based
Build encapsulated components that manage their own state, then compose them to make complex UIs.
Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep state out of the DOM.

***

### Brief Introduction to Related Concepts

* ***React elements*** are JavaScript objects which represent HTML elements. They do not exist in the browser. They represent browser elements such as a `div` or `section`.

* ***Components*** are developer created React elements. They’re usually larger parts of the user interface which contain both the structure and functionality.  *e.g.* a `NavBar`, `LikeButton` or `ImageUploader`.

* ***JSX*** is a technique for creating React elements and components. For example `<h1>Hello</h1>` is a React element written in JSX. The same React element can be written as JavaScript with `React.DOM.h1(null, 'Hello');`. JSX is less effort to read and write and is transformed into JavaScript before running in the browser.

* ***The Virtual DOM*** is a JavaScript tree of React elements and components. React renders the virtual DOM to the browser to make the user interface visible. React observes the virtual DOM for changes and automatically mutates browser DOM to match the virtual DOM.

***

### More details about React
In React you can create components that have special functionality. Each component is contained in its own “scope”, so we can define the functionality of the component and reuse it as many times as we want without them interfering with each other.
Each component has a `render` function, which effectively returns the HTML that the component will render in the browser.
#### Using JSX
Each component has to have a render function. This acts as a “ViewModel” - before you return your HTML for the component, you can manipulate the model information into view information, meaning that your HTML could change drastically depending on the model (e.g. a dynamic repeated list of items).
#### State
Each component has its own “state”. When using state, you define an initial state and then you can update the state using `this.setState`. Whenever the state is updated, the component will call the render function again, and replace/change the difference between the previous render value and the new one. This is where the virtual DOM kicks in - the difference algorithm is done internally in React, so we don’t rely on the DOM updating. React will calculate the difference and produce a sort of instruction set of what to do, and perform them on the DOM.
#### The component lifecycle
Each component has a “lifecycle” - these are a set of functions that you can define in the component’s configuration and they will get called sometime during the components life. 
Here are some lifecycle methods in React:
* `componentWillMount` - Invoked once, on both client & server before rendering occurs.
* `componentDidMount` - Invoked once, only on the client, after rendering occurs.
* `shouldComponentUpdate` - Return value determines whether component should update.
* `componentWillUnmount` - Invoked prior to unmounting component.
