# headless-pdf-renderer

This is a simple HTTP server that offers an endpoint to render
HTML to PDF using Google Chrome with Puppeteer.


### Usage

The default Dockerfile installs all dependencies and runs as
an unprivileged user with Chrome in sandboxed mode.
You can reach the API at `/render` on port 8082.

**NOTICE:** You need to run your container with the `SYS_ADMIN`
capability for the Chrome sandbox to work.