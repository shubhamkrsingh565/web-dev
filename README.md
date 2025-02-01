# web-dev
web development learning series along with projects

# Master React fundamentals
<details>
<summary>1. Core Concepts</summary>
    
  ### What is React?
  
  - Understand React as a JavaScript library for building user interfaces.
  
  - Learn about its declarative and component-based nature.
  
  ### JSX (JavaScript XML)
  
  -  Learn how JSX allows you to write HTML-like syntax in JavaScript.
  
  -  Understand how JSX gets transpiled to React.createElement calls.
  
  ### Components
  
  > Components are the building blocks of a React application. They let you split the UI into independent, reusable pieces.

-  Functional Components: Learn how to create and use functional components.
    - > Functional components are JavaScript functions that return JSX. They are simple and preferred in modern React development.
      - ```
        function Greeting() {
          return <h1>Hello, React!</h1>;
        }
        ```
  -  Class Components: Understand the basics of class components (though functional components are now preferred).
  
  Component Composition: Learn how to compose components to build complex UIs.
  
  ### Props (Properties)
  
  -  Understand how to pass data to components using props.
  
  -  Learn about prop types and default values.
  
  ### State
  
  -  Learn how to manage component-specific data using state.
  
  -  Understand the difference between props and state.
  
  -  Use the useState hook for state management in functional components.
  
  ### Events and Handling
  
  -  Learn how to handle user events (e.g., clicks, input changes) in React.
  
  -  Understand synthetic events in React.

  </details>

<details>
<summary>2. React Hooks</summary>
  
  ### Introduction to Hooks
  
  -  Learn why hooks were introduced and how they simplify state and lifecycle management in functional components.
  
   ### Common Hooks
  
-  **`useState`**: Manage state in functional components.
    
    - useState is a react hook, which create an `state variable`. Which helps us to track state in components & updates the use interface when state changes.
  
  -  **`useEffect`**: Handle side effects (e.g., API calls, subscriptions) in functional components.
  
      -  The `useEffect` hook allows you to perform side effects in your components.
      -  Some examples of side effects are:
            - Fetching data from API
            - Directly updating the DOM
            - Timers like setTimeOut and SetInterval 
  
  -  **`useContext`**: Access context values without prop drilling.
      -  `useContext` is a React Hook that allows you access data from any component without explicitly passing it down through props at every level.
      -  `useContext` is used to managed Global data in the React App.
  
   ### Custom Hooks
  
  -  Learn how to create reusable custom hooks for shared logic.

</details>

<details>
<summary>3. Component Lifecycle</summary>
  
  ### Lifecycle Methods (Class Components)
  
  - Understand lifecycle methods like componentDidMount, componentDidUpdate, and componentWillUnmount.
  
  ### Lifecycle in Functional Components
  
  - Learn how useEffect replaces lifecycle methods in functional components.
</details>

<details>
<summary>4. Conditional Rendering</summary>
  
  - Learn how to conditionally render components or elements based on state or props.

</details>
    
<details>
<summary>5. Lists and Keys</summary>
  
  - Learn how to render lists of data using the map() function.
  
  - Understand the importance of keys for efficient list rendering.

</details>
    
<details>
<summary>6. Forms and Controlled Components</summary>
  
  - Learn how to handle form inputs in React.
  
  - Understand the concept of controlled components (where React manages the form state).

</details>
    
<details>
<summary>7. React Router</summary>

  - Learn how to handle client-side routing using react-router-dom.
  
  - Understand concepts like Route, Link, useNavigate, and useParams.
  
  8. State Management
  Lifting State Up
  
  Learn how to share state between components by lifting it up to a common ancestor.
  
  Context API
  
  Understand how to use the Context API to avoid prop drilling.
  
  Third-Party State Management
  
  Explore libraries like Redux, Zustand, or Recoil for global state management (optional for fundamentals).
  
  9. Styling in React
  Learn different ways to style React components:
  
  Inline styles.
  
  CSS classes.
  
  CSS Modules.
  
  Styled-components or Emotion (CSS-in-JS).
  
  10. Error Boundaries
  Learn how to catch errors in components using error boundaries.
  
  11. React Developer Tools
  Install and use the React Developer Tools browser extension for debugging.
  
  12. Best Practices
  Learn about component reusability and separation of concerns.
  
  Understand the importance of immutability in state updates.
  
  Follow naming conventions and folder structures.
  
  13. Testing
  Learn how to test React components using tools like:
  
  Jest (for unit testing).
  
  React Testing Library (for component testing).
  
  14. Build and Deploy
  Learn how to create a production build using tools like Create React App or Vite.
  
  Deploy your React app to platforms like Netlify, Vercel, or GitHub Pages.
  
  15. Advanced Topics (Optional for Fundamentals)
  Performance Optimization
  
  Learn about React.memo, useMemo, and useCallback.
  
  Code Splitting
  
  Understand how to lazy-load components using React.lazy and Suspense.
  
  Server-Side Rendering (SSR) and Static Site Generation (SSG)
  
  Explore frameworks like Next.js for SSR and SSG.
  
  Resources to Learn React Fundamentals
  Official React Docs: https://react.dev/
  
  FreeCodeCamp React Course: https://www.freecodecamp.org/
  
  Scrimba React Tutorial: https://scrimba.com/learn/learnreact
  
  YouTube Channels: Traversy Media, Academind, The Net Ninja.
  
  By mastering these fundamentals, you'll have a strong foundation to build React applications and explore more advanced topics.
</details>
