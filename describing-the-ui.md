Rendering Lists

- Must create an unique key id
- Keys usually are id's rescued from database

Conditional Rendering

- Must have conditional logics inside the component

Passing Props

- Pass input params to a child component
- Pass output event as a param function from the child to the parent component

JSX inside template HTML

- Must pass javascript values with curly braces "{ }"

Writing Markup with JSX

- HTML Elements must be wrapped inside a fragment or a unique element on the return on the function component

Importing and Exporting Components

- It's recommended to have one component by file, and use "imports" and "exports" to use them into another file component
- Unless u have a small or tightly related to each other
- Never define a component inside another component

Keeping components pure

- Pure functions are:
- Does not change any variable or objects that exists before it was called, or it's own input parameters
- Same input, same output. Given the same input, a pure function should always return the same result
- So, changing variables outside it's scope, it is not a good coding practice
- A way to keep component pure
- All of React components must act as a pure functions in relation to it's props

JSX Markup

- some names are reserved by javascript, names like "class" to define a css class must be
  replaced by "className", in camelCase, to set a JSX tag attribute

JSX Pure functions and side effects

- React's rendering process must always be pure
- So, everytime you call a component with the same inputs but the outputs is differents, it will provoke an side effect
  and the function component is not pure anymore. The component's JSX outputs must be always the same, with the same inputs
- Each component should only "think for itself"
- Three kinds of inputs: props, state and contexts
- Only use local mutation to chage variable
- There is no problem to change variables inside the scope of the component, but it's wronge to change a state of a variable outside of it

- Event handlers don't need to be pure
- Side effects are allowed after rendering phase, and on these case, useEffect hook is a good way to handle it but on a last resort
