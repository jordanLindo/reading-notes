# Reading Notes class-02

By understanding the order that actions occur some logic errors can be avoided, and the expected result can be reached.

## React lifecycle

1. render occurs prior to componentDidMount.
2. constructor is the first thing in the lifecycle.
3. constructor, render, React updates, componentDidMount, componentWillUnmount
4. componentWillUnmount removes the component from the DOM.

## React State Vs Props

1. A key and value pair is passed.
2. Props is passed in, and state is handled inside the component.
3. When state changes.
4. A counter, or a some other information that changes based on a users actions within a component.
