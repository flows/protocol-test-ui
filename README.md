# FBP Protocol Test Interface

Example:

http://flows.github.io/protocol-test-ui/

Install graph dependencies:
`fbpx install graphs/ui.fbp`

`fbpx browserify graphs/ui.fbp > www/ui.js`

Watch:
`fbpx browserify graphs/ui.fbp --watch -o www/ui.js`

Watch and reload with fb-flo:

`fbpx browserify graphs/ui.fbp --watch --browser -o www/ui.js`

Serve index.html
`http-server www/`

Still to implement:

`fbpx serve graphs/ui.fbp --watch --browser -o www/ui.js`
