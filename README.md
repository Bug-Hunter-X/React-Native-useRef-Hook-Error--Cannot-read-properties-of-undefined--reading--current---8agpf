# React Native useRef Hook Error: Cannot read properties of undefined (reading 'current')

This repository demonstrates a common error encountered when using the `useRef` hook in React Native: the 'Cannot read properties of undefined (reading 'current')' error.  This happens when a component unmounts before an asynchronous operation within the `useRef` callback completes.

The `unmountedRefBug.js` file showcases the problematic code. The `unmountedRefSolution.js` file provides a corrected version that avoids the error using the `useEffect` hook and cleanup function to manage the asynchronous operation.

## Steps to Reproduce
1. Clone the repository.
2. Run `npm install`.
3. Run the app using a React Native simulator or device.
4. Observe the error in the console (in the buggy version).
5. Compare the corrected solution to see how the issue is resolved.