# Closure-based OpenLayers 3 Application

This is the sample application developed for the tutorial
[Compiling Application with Closure Compiler](http://openlayers.org/en/latest/doc/tutorials/closure.html).

To install the required dependencies, run:

    npm install

To compile the code:

    ./node_modules/.bin/closure-util build config.json app.js

This creates the build in `app.js`. Open `index.html` to check if
the build works correctly.

To start the development server, run:

    ./node_modules/.bin/closure-util serve config.json

Then open [http://localhost:3000/index-debug.html](http://localhost:3000/index-debug.html) in a browser.
