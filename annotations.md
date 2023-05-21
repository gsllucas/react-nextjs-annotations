I'll let here important annotations according the studies advances

- Why start a project and use one of the recommended react frameworks, like nextjs, gatsby, etc

A: because as the way the app grows, it is more probably the necessity of having routing,
data fetching and rendering strategies as server side rendering. As also because of optimized setups
like code-splitting, bundles and etc.

Getting Started

How to create and nest components

- Components are javascript functions, and must be created with PascalCase
- Components declarations/definitions must never be declared inside other componenents

How to add markup and styles

- One of the best ways to include css styles is the css modules, because the scope of
  stylyshing and classes name, that cannot colide with another component's class name.

- Pode-se utilizar o atributo de style com curly braces e objeto dentro quando for necessçãrio
  utilizar algum valor javascript que será passado para o css

How to display data

- Use curly braces to reference javascript value (variables) into the html file

How to render conditions and lists

- Generate an unique for iterations
- Conditionals is just like as an if statement

How to respond to events and update the screen

- Must include 'use client' to tell react the app is going to use browser events

How to update the screen

- Built-in hook useState to update the entire component

Hooks

- Hooks are more restrictive than other functions
- Must be called on the top of component function, or other custom hook
- Don't use on loops or conditionals, must be extracted inside the generated component

How to share data between components
