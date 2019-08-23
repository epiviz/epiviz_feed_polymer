# Epiviz feed UI

This repository contains the user interface that is part of the Epiviz Feed framework. This application is built using Google Polymer, a web component framework library to build modular and resuable user interface components. 

## Getting Started

### Installation requirements

Follow instructions to install [Google Polymer](https://www.polymer-project.org/) and [bower](https://bower.io/) for building this repository.

To install dependencies, run

`bower install`

To build the application

`polymer build`

### Serving the application from the build

The build process generates a new folder `build` inside this repository. you can now host this app through apache or run a local server using php or python to serve the application.

using php

`php -S localhost:7782`

using python

`python -m SimpleHTTPServer`

