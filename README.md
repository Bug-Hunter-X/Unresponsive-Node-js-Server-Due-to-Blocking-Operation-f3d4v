# Unresponsive Node.js Server Due to Blocking Operation

This repository demonstrates a common issue in Node.js applications: an unresponsive server caused by a long-running synchronous operation that blocks the event loop.  The provided `bug.js` file contains a simple HTTP server with a request handler that simulates a long-running task, preventing the server from responding to other requests.

The `bugSolution.js` file offers a solution using asynchronous operations to prevent blocking the event loop.