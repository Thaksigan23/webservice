![Screenshot 2025-04-09 213942](https://github.com/user-attachments/assets/f696adde-132d-4b9a-bede-c537b5e92582)
The terminal output indicates that your Node.js server started successfully and then shut down.

Details:
Command Executed: node index.js

Directory: C:\Users\thaks\OneDrive\Desktop\DAY08

Debugger: Attached during execution

Server Status: Started on port 3001

Shutdown Status: The process ended with message:
"Waiting for the debugger to disconnect..."

This means the server launched correctly but was likely stopped manually or exited after completing a task. If this wasn't intentional, double-check:

There's no process.exit() or unhandled error in index.js.

Debugger settings or breakpoints didn’t cause early exit.
