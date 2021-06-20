# What Is React?

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.

The render method returns a description of what you want to see on the screen. React takes the description and displays the result. In particular, render returns a React element, which is a lightweight description of what to render. Most React developers use a special syntax called “JSX” which makes these structures easier to write. The <div /> syntax is transformed at build time to React.createElement('div').

# What is a component?

A React component is a reusable piece of code used to define the appearance, behavior, and state of a portion of a web app’s interface. Components are defined as functions or as classes. Using the component as a factory, an infinite number of component instances can be created.

 **Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components. You can find a detailed component API reference here.**

 **Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen.**


 ### Function and Class Components
 This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions

 ### Rendering a Component
 Previously, we only encountered React elements that represent DOM tags:

*-const element = <div />;_*

However, elements can also represent user-defined components:

*_const element = <Welcome name="Sara" />;_*

When React sees an element representing a user-defined component, it passes JSX attributes and children to this component as a single object. We call this object “props”.
 

 ### Composing Components

 Components can refer to other components in their output. This lets us use the same component abstraction for any level of detail. A button, a form, a dialog, a screen: in React apps, all those are commonly expressed as components.

 ### Extracting Components

 Extracting components might seem like grunt work at first, but having a palette of reusable components pays off in larger apps. A good rule of thumb is that if a part of your UI is used several times (Button, Panel, Avatar), or is complex enough on its own (App, FeedStory, Comment), it is a good candidate to be extracted to a separate component.

 **so we can say  the advantages of using component based architecture is to make your code readable and easy to read.**


 # Props are Read-Only

Whether you declare a component as a function or a class, it must never modify its own props. Consider this sum function:

*_function sum(a, b) {
  return a + b;
}_*

Such functions are called “pure” because they do not attempt to change their inputs, and always return the same result for the same inputs.

In contrast, this function is impure because it changes its own input:

*_function withdraw(account, amount) {
  account.total -= amount;
}_*

React is pretty flexible but it has a single strict rule:

All React components must act like pure functions with respect to their props.

Of course, application UIs are dynamic and change over time. In the next section, we will introduce a new concept of “state”. State allows React components to change their output over time in response to user actions, network responses, and anything else, without violating this rule.
