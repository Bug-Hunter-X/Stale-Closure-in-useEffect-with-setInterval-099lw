# Stale Closure Bug in React's useEffect Hook

This repository demonstrates a common bug in React applications involving the `useEffect` hook and `setInterval`.  The issue arises from stale closures, where the `count` variable inside the `setInterval` callback refers to the initial value of `count`, not the updated value.  This leads to incorrect counter behavior.

The `bug.js` file shows the buggy implementation, while `bugSolution.js` provides the corrected code.