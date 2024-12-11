This repository demonstrates a common yet easily overlooked error in Node.js applications using Express.js and promises: unhandled promise rejections.  The `bug.js` file showcases an Express.js server with an asynchronous operation that may fail.  Crucially, it lacks proper error handling for the promise's rejection, leading to silent failures and potential instability.  The `bugSolution.js` file presents the corrected code with robust error handling.