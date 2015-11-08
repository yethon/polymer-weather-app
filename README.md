
## Polymer Weather Application

An experimental app built with [Polymer](http://polymer-project.org) and [Firebase open data sets](https://www.firebase.com/docs/open-data/weather.html).

Based off of the [Polymer Starter Kit](https://github.com/polymerelements/polymer-starter-kit/releases/latest).


### Run the app...

**Start with these instructions (taken from the Polymer Starter Kit project)**

1)  Check your Node.js version.

```sh
node --version
```

The version should be at or above 0.12.x.

2)  If you don't have Node.js installed, or you have a lower version, go to [nodejs.org](https://nodejs.org) and click on the big green Install button.

3)  Install `gulp` and `bower` globally.

```sh
npm install -g gulp bower
```

Install [Node](https://nodejs.org/)

Clone this repo, and

With Node.js installed, run the following one liner:

```sh
npm install -g gulp bower && npm install && bower install
```

### Development workflow

#### Serve / watch

```sh
gulp serve
```

This outputs an IP address you can use to locally test and another that can be used on devices connected to your network.

#### Build & Vulcanize

```sh
gulp
```

Build and optimize the current project, ready for deployment. This includes linting as well as vulcanization, image, script, stylesheet and HTML optimization and minification.
