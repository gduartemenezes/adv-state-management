# Ellegant Context

Ellegant Context is a React project that demonstrates the power and flexibility of the **Context API** in combination with the **useReducer** hook. The goal of this project is to show how developers can effectively manage global state in React applications without having to rely on cumbersome "prop drilling."

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Benefits of Context API](#benefits-of-context-api)
- [Avoiding Prop Drilling](#avoiding-prop-drilling)
- [License](#license)

## Introduction
In modern React development, managing state across various components can quickly become challenging as your application grows. **Ellegant Context** aims to simplify state management using the **React Context API** and **useReducer** hook. This combination allows for a more advanced and structured way to handle global states without needing third-party libraries like Redux.

## Features
- Demonstrates the use of the **Context API** for state management.
- Uses the **useReducer** hook for complex state transitions.
- Avoids **prop drilling** by providing a global state accessible from any component.
- Lightweight and built with **Vite** for blazing-fast development.

## Getting Started

### Prerequisites
Make sure you have the following tools installed on your machine:
- **Node.js** (version 14 or above)
- **npm** or **yarn**

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/gduartemenezes/adv-state-management.git
   cd adv-state-management
   npm install
   npm run dev 

## Usage
This project serves as an example of how the Context API and useReducer hook work together to manage state across various components. To see the project in action:

Check out the provided components and how they consume the global state.
Experiment by adding new actions to the useReducer and see how state transitions are handled globally.
## Benefits of Context API
The Context API in React allows developers to create a shared state that can be accessed by any component within the tree, no matter how deeply nested. This offers several advantages:

Global State Management: Instead of passing state down through props, the Context API allows you to define global states that can be consumed by any component.
Separation of Concerns: You can decouple the logic that manages your app's state from the components that consume that state, making your app easier to maintain.
Custom Context Providers: Developers can create custom providers that contain specific logic for particular types of state, which can then be reused across the application.
## Avoiding Prop Drilling
In React, prop drilling occurs when data is passed from one component to another through multiple layers of child components. This can make code harder to manage and debug. The Context API helps to avoid this by allowing state to be stored in a context provider and accessed directly from any component, regardless of its position in the component tree.

By using Context API:

You can provide global state and functions to any part of your application without having to pass them as props at every level.
This keeps your codebase clean and reduces unnecessary prop-passing, especially in larger projects with deep component hierarchies.
## License
This project is licensed under the MIT License.