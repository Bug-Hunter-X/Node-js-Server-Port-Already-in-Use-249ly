# Node.js Server Port Already in Use

This repository demonstrates a common issue in Node.js development:  a server failing to start because the specified port is already in use.  The provided `bug.js` file shows the problematic code, and `bugSolution.js` offers a robust solution.

## Problem

The `bug.js` file attempts to start a simple HTTP server on port 8080. If another application is using this port (e.g., another instance of the server or a different service), the server will fail to start.  The error message can be cryptic, often simply hanging the program or producing a less-than-helpful error.