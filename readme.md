# Epiviz feed User Interface

This repository contains the user interface that is part of the Epiviz Feed framework. This application is built using Google Polymer, a web component framework library to build modular and resuable user interface components. 

## Installation

Follow instructions to install [Google Polymer](https://www.polymer-project.org/) and [bower](https://bower.io/) for building or running this repository.

To install dependencies, run

`bower install`

## Running the application on local machine

Run

`polymer serve`

which will serve the application, the default port is 8081. You may now access through localhost:8081 to access the interface.

NOTE: you also need to run the computation server to have full functionality of the application.

## Serving the application from the build

The application can also be served from build using common web servers.

To build the application

`polymer build`

The build process generates a new folder `build` inside this repository. you can now host this app through apache or run a local server using php or python to serve the application.

using php

`php -S localhost:7782`

using python

`python -m SimpleHTTPServer`

