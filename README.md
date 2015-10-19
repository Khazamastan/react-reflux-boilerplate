# React Reflux Boilerplate

Another template that makes react and reflux web app developmet easier.

## Demo

[Click here for demo](http://xuqingkuang.github.io/react-reflux-boilerplate)

## Features

* React 0.14
* React Router 1.0.0
* Reflux 0.3.0 ( Refactor of Flux )
* Node 4.1 Compatible
* Babel 5.8 for ES7 support
* Browser Live Reload based on react-transform-hmr, it build codes pretty fast!
* CSS / HTML / JS minification / Image optimization when built
* JS code duplication removal during built
* Code is minimized and pure write with Javascript ES7, focused on core features only.

If you are interested, please read the `package.json` file for all installed modules.

Feel free to contribute or fork it if you find this repo could help the community.

## TODO

* Jest ( Testing framework for React app )

## Installation

### Requirements

* Node 4.0 is required for better experiences, previous versions maybe compatible but not tested yet.
* Gulp must be installed globally with `$ npm install -g gulp`

### Start

1. Clone the repo - `$ git clone https://github.com/xuqingkuang/react-reflux-boilerplate`
2. Install the requirements - `$ cd react-reflux-boilerplate && npm install`

### Commands / Gulp Tasks

#### Start develop environment

```$ gulp```

Run gulp directly without any options will build the codes and start a
development web server on `http://localhost:8000`, then you can open a browsre to
access the page, the codes in `src` will be compiled at run time when change
anything, and the browser will auto reload.

By the way, the step is running on memory, there's no any files generated.

#### Build the codes for production

```$ gulp production```

The codes will be compiled and placed to `public` folder, all of them are minimized.

####  Clean the built folder

```$ gulp clean```

The all files in `public` folder will be removed.

### Structure

1. `src/`       - all of sources
2. `assets/`    - all of static files
3. `public/`    - built minimized codes, for production environment.

__Note__ : `assets/` and `src/` will be compiled into public/ folder when you run `gulp production` command.
