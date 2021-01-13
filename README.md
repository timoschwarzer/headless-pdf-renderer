# headless-pdf-renderer

This is a simple HTTP server that offers an endpoint to render
HTML to PDF using Google Chrome with Puppeteer.


### Usage

The default Dockerfile installs all dependencies and runs as
an unprivileged user with Chrome in sandboxed mode.
You can reach the API at `/render` on port 8082.

See my blog post for more usage information: https://blog.timo.page/rendering-html-to-pdf-in-laravel-and-docker
