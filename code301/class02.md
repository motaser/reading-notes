## State and Lifecycle

**What is State?**

State is used with React Component Classes to make them dynamic. It enables the component to keep track of changing information in between renders. More specifically, the state of a component is an object that holds information that may change over the lifetime of the component.

**State v Props**


You may wonder how this differs from props? We looked at props in my previous article: React: Components & Props. Recall that props are an object which holds information to control a components behavior. This sounds very similar to state, but lets see how they differ:
Props are immutable. Once set they can’t be changed
State is observable. It can hold data that may change over time
Props can be used in either function or class components
State is limited to class components
Props are set by the parent component
State is updated by event handlers
Using State
When using State, we need the state of a component to always exist — so we need to set an initial state. We can do so by defining our state in the constructor of our component class, like so:


*_class MyClass extends React.Component {
  constructor(props){
    super(props);
    this.state = { attribute : "value" };
  }
} _*


**Lifecycle**


In the next section, we’re going to take a look at the React lifecycle. Lets start with a definition..

**What is the lifecycle?**


In general, we might define a lifecycle as birth, growth & death. And our React components follow this cycle as well: they’re created (mounted on the DOM), they experience growth (by updating) and they die (unmounted from the DOM). This is the component lifecycle!
Within the lifecycle of a component, there are different phases. These phases each have their own lifecycle methods. Lets now take a look at these methods.
The Lifecycle Methods
A component’s lifecycle can be broken down into four parts:
* Initialization
* Mounting
* Updating
* Unmounting

![image](https://i.stack.imgur.com/9rwpx.png)