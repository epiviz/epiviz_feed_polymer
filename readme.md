# EpiViz_Polymer_feed

Polymer feed container for epiviz.

## Getting Started

### Right now you can run the build instead of intalling all the packages locally

The build is contained in `build/default` folder. You may just run a simple http server in `build/default` folder to serve the page (instead of using polymer serve). For example, if use a python server, within `build/default` folder, you may run:

`python -m SimpleHTTPServer`

This runs the http server in default port `8000`. You may go to browser and route to `localhost:8000` to see the page. 

### Installation

You should have node.js, npm, polymer-cli, and polymer installed first.

Then install all the dependency packages through `bower`

`bower install`

To start watching the files, run:

`polymer serve`


This is an initial commit and right now it's under development, more to come soon.
