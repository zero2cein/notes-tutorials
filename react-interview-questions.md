| **Questions**   | Answers |
| -------- | ----------- |
| **What is a virtual DOM?** | |
| **What is the difference between props and state?** | Props are used to pass data between components where as state is for data to be used by the component itself.|
| **What is a React Fragment?** | In React, we can only return 1 node from the render method. A React fragment lets you group a list of children without adding extra nodes to the DOM. Syntax: **<React.Fragment>...nodes<React.Fragment> or <>...nodes<>** |
| **What is an Error Boundary?** |Error boundaries are React components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the component tree that crashed. Error boundaries catch errors during rendering, in lifecycle methods, and in constructors of the whole tree below them [Error Boundaries](https://reactjs.org/docs/error-boundaries.html) |
| **How to do multiple exports from index.js**| ```export {default as statesList} from "./states.list";``` in index.js| 
