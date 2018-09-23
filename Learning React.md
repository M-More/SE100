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

### More about React Components
In React you can create components that have special functionality. Each component is contained in its own “scope”, so we can define the functionality of the component and reuse it as many times as we want without them interfering with each other.
Each component has a `render` function, which effectively returns the HTML that the component will render in the browser.
#### Using JSX
Each component has to have a render function. This acts as a “ViewModel” - before you return your HTML for the component, you can manipulate the model information into view information, meaning that your HTML could change drastically depending on the model (e.g. a dynamic repeated list of items).
#### State
Every component has a `state` object and a `props` object. State is set using the `setState` method. Calling `setState` triggers UI updates and is the bread and butter of React's interactivity. If we want to set an initial state before any interaction occurs we can use the `getInitialState` method. Below, see how we can set our component's state:

```javascript
var MyComponent = React.createClass({
    getInitialState: function(){
        return {
            count: 5
        }
    },
    render: function(){
        return (
            <h1>{this.state.count}</h1>
        )
    }
});
```

#### The component lifecycle
Each component has a “lifecycle” - these are a set of functions that you can define in the component’s configuration and they will get called sometime during the components life. 
Here are some lifecycle methods in React:
* `componentWillMount` - Invoked once, on both client & server before rendering occurs.
* `componentDidMount` - Invoked once, only on the client, after rendering occurs.
* `shouldComponentUpdate` - Return value determines whether component should update.
* `componentWillUnmount` - Invoked prior to unmounting component.

#### Component Methods
React also offers us methods for our components to make our lives much easier. These are called on the creation of the component. For example, `getInitialState`, which allows us to define a default state so we don’t have to worry about checking if the state item exists further down the line.
* `getInitialState` - Return value is the initial value for state.
* `getDefaultProps` - Sets fallback props values if props aren't supplied.
* `mixins` - An array of objects, used to extend the current component's functionality.

***

### Pros & Cons of React
#### Pros

1.  Virtual DOM in ReactJS makes user experience better and developer’s work faster
2.  Permission to reuse React components significantly saves time
3.  One-direction data flow in ReactJS provides a stable code
4.  An open-source Facebook library: constantly developing and open to the community
5.  Wide React and Redux toolset

#### Cons
1.  High pace of development
2.  Poor documentation
3.  JSX’s complexity and consequent steep learning curve


***

### Conclusion
React is an insanely powerful framework.Implementing a virtual DOM, it allows us to render components super fast whilst removing any unnecessary overhead from DOM operations.
