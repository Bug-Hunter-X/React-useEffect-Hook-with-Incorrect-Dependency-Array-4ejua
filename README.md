# React useEffect Hook with Incorrect Dependency Array

This repository demonstrates a common React bug involving the `useEffect` hook and its dependency array.  The provided `MyComponent` initially logs 'Effect runs on every render' each time the component renders, even though it should only run once on mount. This is because the dependency array is empty (`[]`), causing unnecessary re-renders and potential performance issues.

The solution shows how to correctly specify the dependency array to control when the effect runs.

## Setup:

1. Clone this repository.
2. Navigate to the directory: `cd react-useeffect-bug`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`