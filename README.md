# FBP Protocol Test Interface

Install graph dependencies:
`fbpx install graphs/ui.fbp`

`fbpx browserify graphs/ui.fbp > example/ui.js`

Watch:
`fbpx browserify graphs/ui.fbp --watch -o example/ui.js`

Watch and reload with fb-flo:

`fbpx browserify graphs/ui.fbp --watch --browser -o example/ui.js`

Serve index.html
`http-server example/`

Still to implement:

`fbpx serve graphs/ui.fbp --watch --browser -o example/ui.js`
