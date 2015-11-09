
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

#### Serve build

If you decide to create a Polymer app, you should periodically serve the
built code.  You might find that even though your app can be served
without any errors while you develop (using gulp serve), the built code
throws errors.  Since the errors are being thrown by minified\uglified
files, you will never know what's wrong :o) but the 'vulcanization' step is probably to blame.

```sh
gulp serve:dist
```

#### Build & Vulcanize

```sh
gulp
```

Build and optimize the current project, ready for deployment. This includes linting as well as vulcanization, image, script, stylesheet and HTML optimization and minification.
