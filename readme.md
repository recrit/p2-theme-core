[![Read the Docs Badge](https://readthedocs.org/projects/p2-theme-core/badge/?version=latest)](http://p2-theme-core.readthedocs.org/en/latest/?badge=latest) [![Build Status](https://travis-ci.org/phase2/p2-theme-core.svg?branch=master)](https://travis-ci.org/phase2/p2-theme-core)

[![NPM](https://nodei.co/npm/p2-theme-core.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/p2-theme-core)

[![NPM](https://nodei.co/npm-dl/p2-theme-core.png?months=6)](https://nodei.co/npm/p2-theme-core)

# Prerequisites

- [Node](https://nodejs.org) v4 OR v6 (the two [LTS](https://github.com/nodejs/LTS) versions)

**This is one of two pieces of our themes:**

- [`pattern-lab-starter`](https://github.com/phase2/pattern-lab-starter) - a starter set of files for Drupal theming that includes a Twig powered Pattern Lab and beginning Sass & other front end tools. Uses `p2-theme-core` for automation. 
- [`p2-theme-core`](https://github.com/phase2/p2-theme-core) (this repo) - the core gulp tasks that handles most of the theme's automation.

# Phase2 Theme Core

Here is the core gulp tasks used in our themes that are generated by `yo p2-theme`. Ideally, the changes to how a theme install works would be done by passing in a different `config.yml`. 

**More docs in [`docs/`](https://github.com/phase2/p2-theme-core/tree/master/docs) folder – these docs are [hosted in Read the Docs](http://p2-theme-core.readthedocs.org)!**

# Features

- Scss => CSS compiling with Libsass, PostCSS, linting, and SourceMaps
- Pattern Lab Twig compiling & BrowserSync live reload and style injection
- SVG => Font Icons compiling with support for adding mixins and classes to Scss along with a demo page in Pattern Lab
- JS compiling via Babel, linting and aggregation
- Drupal file watching to trigger Drush cache clears

All is easily configurable by changing values in your `config.yml` file in your project. These values are merged into the `config.default.yml` file - look there for the available options and defaults.
