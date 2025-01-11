# Technical Questions for IT Job Interviews (Frontend/React Developer)

---

## HTML Questions

1. **What is the difference between `<div>` and `<section>`?**
   - **Solution**: 
     - `<div>`: Generic container for grouping elements without semantic meaning.
     - `<section>`: Represents a specific section of content with semantic meaning.

2. **What are semantic tags in HTML?**
   - **Solution**: Tags that clearly define their content (e.g., `<header>`, `<footer>`, `<article>`). They improve accessibility and SEO.

3. **What is the difference between `id` and `class` in HTML?**
   - **Solution**:
     - `id`: Unique identifier, applied to one element.
     - `class`: Reusable across multiple elements.

4. **What are data attributes in HTML?**
   - **Solution**: Attributes starting with `data-` to store custom data, e.g., `<div data-user-id="123">`.

---

## CSS Questions

1. **What is the difference between relative, absolute, and fixed positioning in CSS?**
   - **Solution**:
     - **Relative**: Positioned relative to itself.
     - **Absolute**: Positioned relative to the nearest positioned ancestor.
     - **Fixed**: Positioned relative to the viewport and doesn’t move when scrolling.

2. **What is the difference between `inline`, `block`, and `inline-block` elements?**
   - **Solution**:
     - **Inline**: Doesn't start on a new line, only as wide as its content (e.g., `<span>`).
     - **Block**: Starts on a new line, takes full width (e.g., `<div>`).
     - **Inline-block**: Combines inline behavior with the ability to set dimensions.

3. **What is the difference between `px`, `em`, and `rem`?**
   - **Solution**:
     - `px`: Absolute unit (fixed size).
     - `em`: Relative to the parent element's font size.
     - `rem`: Relative to the root element's font size.

4. **What is Flexbox, and why is it used?**
   - **Solution**: A CSS layout model for creating responsive designs by aligning items in rows or columns with properties like `justify-content`, `align-items`, and `flex-wrap`.

5. **What is the difference between `CSS Grid` and `Flexbox`?**
   - **Solution**:
     - **Grid**: For two-dimensional layouts (rows and columns).
     - **Flexbox**: For one-dimensional layouts (row or column).

---

## JavaScript Questions

1. **What is the difference between `var`, `let`, and `const`?**
   - **Solution**:
     - `var`: Function-scoped, hoisted.
     - `let`: Block-scoped, can be updated.
     - `const`: Block-scoped, cannot be updated.

2. **What is the difference between `==` and `===`?**
   - **Solution**:
     - `==`: Checks equality after type coercion.
     - `===`: Checks equality without type coercion.

3. **What is the DOM, and how do you manipulate it?**
   - **Solution**: 
     - The DOM is the tree-structured representation of a web page.
     - Methods to manipulate: `getElementById`, `querySelector`, `appendChild`, `removeChild`.

4. **What are closures in JavaScript?**
   - **Solution**: A closure is when an inner function retains access to variables of its outer function even after the outer function has executed.

5. **What is the difference between synchronous and asynchronous programming?**
   - **Solution**:
     - **Synchronous**: Code is executed sequentially.
     - **Asynchronous**: Code doesn’t wait; functions like `setTimeout` or `Promises` are used.

---

## React Questions

1. **What is React, and why is it used?**
   - **Solution**: React is a JavaScript library for building user interfaces. It uses a virtual DOM for efficient updates and a component-based architecture for reusability.

2. **What are the differences between functional and class components in React?**
   - **Solution**:
     - Functional: Stateless components using hooks for state and lifecycle (e.g., `useState`, `useEffect`).
     - Class: Components with `state` and lifecycle methods (`componentDidMount`, etc.).

3. **What are props in React?**
   - **Solution**: Props are inputs to a component, passed from a parent component to make it dynamic.

4. **What is the difference between state and props?**
   - **Solution**:
     - **State**: Local to the component, mutable.
     - **Props**: Passed from parent, immutable.

5. **What are React hooks?**
   - **Solution**: Hooks are functions that allow functional components to use React features:
     - `useState`: Manage state.
     - `useEffect`: Perform side effects.
     - `useContext`: Access global state.

6. **What is the virtual DOM?**
   - **Solution**: A lightweight representation of the real DOM that React updates first, minimizing changes to the real DOM for better performance.

7. **What is the difference between `useEffect` and `useLayoutEffect`?**
   - **Solution**:
     - `useEffect`: Runs after render (non-blocking).
     - `useLayoutEffect`: Runs synchronously after DOM updates (blocking).

8. **What is Redux, and why is it used?**
   - **Solution**: Redux is a state management library used for managing global state across a React app.

9. **What are higher-order components (HOC) in React?**
   - **Solution**: HOCs are functions that take a component as input and return a new component, enhancing it with additional functionality.

10. **How do you handle forms in React?**
    - **Solution**: By using controlled components:
      ```jsx
      const [value, setValue] = useState("");
      return (
        <input value={value} onChange={(e) => setValue(e.target.value)} />
      );
      ```

---

## Other Technical Questions

1. **What is responsive design?**
   - **Solution**: Ensuring a website works on different devices using media queries and flexible layouts.

2. **What is REST API, and how do you use it?**
   - **Solution**: REST APIs are a way to communicate between frontend and backend. Use `fetch` or `axios` to make HTTP requests.

3. **How do you optimize website performance?**
   - **Solution**:
     - Minimize CSS/JS.
     - Use lazy loading for images.
     - Cache data.
     - Reduce HTTP requests.

---

Let me know if you'd like more examples or deeper explanations!
