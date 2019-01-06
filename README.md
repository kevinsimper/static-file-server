# static-file-server

I believe in that you should build your own tools, both for learning but also to allow you to serve your own goals.

I have used different static file servers over the years and they have sometimes diverted away from being simply or not solving the right problems.

## Design goals:

This is what the file server has define to solve:

- serve files
- always choose a free port
- not writing any files in production - readonly filesystem
- a way to enable cors
- 404 customizable page
