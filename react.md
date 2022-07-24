# React Notes
## React Hooks
- Hooks allow *function components* to have access to state and other React features
- Hooks allow us to "hook" into React features such as state and lifecycle methods.
- Hooks can only be called at the top level of a component.
- Hooks cannot be conditional

1. **useState**: 
Same as Class variables in Angular. Used for creating variables that can be updated safely and then rendered in UI. [Click here to read more](https://dev.to/glebirovich/angular-in-react-terms-component-state-1d5k)
## Errors & Fixes
|                |Error                          |Fix                         |
|----------------|-------------------------------|-----------------------------|
|1|**Warning: A component is changing an uncontrolled input to be controlled. This is likely caused by the value changing from undefined to a defined value, which should not happen. Decide between using a controlled or uncontrolled input element for the lifetime of the component.**|A html element was set to undefined when created and has now been given a value. Fix: Initialize with some default value( e.g. '')            |
|2          |**Warning: Component contains an input of type text with both value and defaultValue props. Input elements must be either controlled or uncontrolled (specify either the value prop, or the defaultValue prop, but not both). Decide between using a controlled or uncontrolled input element and remove one of these props.**           |Remove defaultValue. defaultValue can come from state property's initial value.|
|3          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|
