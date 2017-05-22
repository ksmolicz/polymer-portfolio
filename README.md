# Polymer portfolio

Simple portfolio page created with just Polymer web components.

For fun with love.
Demo: https://portfolio-8d851.firebaseapp.com/

### Setup

### Build

This command performs HTML, CSS, and JS minification on the application
dependencies, and generates a service-worker.js file with code to pre-cache the
dependencies based on the entrypoint and fragments specified in `polymer.json`.
The minified files are output to the `build/unbundled` folder, and are suitable
for serving from a HTTP/2+Push compatible server.

In addition the command also creates a fallback `build/bundled` folder,
generated using fragment bundling, suitable for serving from non
H2/push-compatible servers or to clients that do not support H2/Push.

    polymer build

### Start the development server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve



