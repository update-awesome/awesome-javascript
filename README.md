# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sorrycc/awesome-javascript/)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Component management](#component-management)
  * [Loaders](#loaders)
  * [Bundlers](#bundlers)
  * [Type Checkers](#type-checkers)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
  * [Templating Engines](#templating-engines)
  * [Articles/Posts](#articles-and-posts)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
    * [Spreadsheet](#spreadsheet)
  * [Editors](#editors)
  * [Documentation](#documentation)
  * Utilities
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structure](#data-structure)
    * [Date](#date)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#videoaudio)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Streaming](#streaming)
    * [Vision Detection](#vision-detection)
    * [Browser Detection](#browser-detection)
    * [Operating System](#operating-system)
    * [Benchmark](#benchmark)
    * [Machine Learning](#machine-learning)
  * UI
    * [Code Highlighting](#code-highlighting)
    * [Loading Status](#loading-status)
    * [Validation](#validation)
    * [Keyboard Wrappers](#keyboard-wrappers)
    * [Tours And Guides](#tours-and-guides)
    * [Notifications](#notifications)
    * [Sliders](#sliders)
    * [Range Sliders](#range-sliders)
    * [Form Widgets](#form-widgets)
    * [Tips](#tips)
    * [Modals and Popups](#modals-and-popups)
    * [Scroll](#scroll)
    * [Menu](#menu)
    * [Table/Grid](#tablegrid)
    * [Frameworks](#frameworks-1)
    * [Boilerplates](#boilerplates)
    * [Image](#image)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [Generators](#generators)
  * [Full Text Search](#full-text-search)
  * [SDK](#sdk)
  * [Misc](#misc)
  * [Podcasts](#podcasts)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----


## Package Managers
*Host the JavaScript libraries and provide tools for fetching and packaging them.*

* [npm](https://www.npmjs.com/) - npm is the package manager for JavaScript.
* <code>&nbsp;15063</code> ![](https://img.shields.io/github/last-commit/bower/bower) [Bower](https://github.com/bower/bower) - A package manager for the web.
* <code>&nbsp;&nbsp;4584</code> ![](https://img.shields.io/github/last-commit/componentjs/component) [component](https://github.com/componentjs/component) - Client package management for building better web applications.
* <code>&nbsp;&nbsp;&nbsp;909</code> ![](https://img.shields.io/github/last-commit/spmjs/spm) [spm](https://github.com/spmjs/spm) - Brand new static package manager.
* <code>&nbsp;&nbsp;1511</code> ![](https://img.shields.io/github/last-commit/caolan/jam) [jam](https://github.com/caolan/jam) - A package manager using a browser-focused and RequireJS compatible repository.
* <code>&nbsp;&nbsp;3726</code> ![](https://img.shields.io/github/last-commit/jspm/jspm-cli) [jspm](https://github.com/jspm/jspm-cli) - Frictionless browser package management.
* <code>&nbsp;&nbsp;1785</code> ![](https://img.shields.io/github/last-commit/ender-js/Ender) [Ender](https://github.com/ender-js/Ender) - The no-library library.
* <code>&nbsp;&nbsp;1401</code> ![](https://img.shields.io/github/last-commit/volojs/volo) [volo](https://github.com/volojs/volo) - Create front end projects from templates, add dependencies, and automate the resulting projects.
* <code>&nbsp;&nbsp;3459</code> ![](https://img.shields.io/github/last-commit/duojs/duo) [Duo](https://github.com/duojs/duo) - Next-generation package manager that blends the best ideas from Component, Browserify and Go to make organizing and writing front-end code quick and painless.
* [yarn](https://yarnpkg.com/) - Fast, reliable, and secure dependency management.
* [pnpm](https://pnpm.io/) - Fast, disk space efficient package manager.


## Component Management

* <code>&nbsp;15047</code> ![](https://img.shields.io/github/last-commit/teambit/bit) [Bit](https://github.com/teambit/bit) - Create, find and reuse components (React, Angular, Node etc.) across applications.

## Loaders
*Module or loading system for JavaScript.*

* <code>&nbsp;12776</code> ![](https://img.shields.io/github/last-commit/requirejs/requirejs) [RequireJS](https://github.com/requirejs/requirejs) - A file and module loader for JavaScript.
* <code>&nbsp;14045</code> ![](https://img.shields.io/github/last-commit/substack/node-browserify) [browserify](https://github.com/substack/node-browserify) - Browser-side require() the node.js way.
* <code>&nbsp;&nbsp;8212</code> ![](https://img.shields.io/github/last-commit/seajs/seajs) [SeaJS](https://github.com/seajs/seajs) - A Module Loader for the Web.
* <code>&nbsp;&nbsp;4176</code> ![](https://img.shields.io/github/last-commit/headjs/headjs) [HeadJS](https://github.com/headjs/headjs) - The only script in your HEAD.
* <code>&nbsp;&nbsp;1892</code> ![](https://img.shields.io/github/last-commit/cujojs/curl) [curl](https://github.com/cujojs/curl) - A small, fast, extensible module loader that handles AMD, CommonJS Modules/1.1, CSS, HTML/text, and legacy scripts.
* <code>&nbsp;&nbsp;1394</code> ![](https://img.shields.io/github/last-commit/rgrove/lazyload) [lazyload](https://github.com/rgrove/lazyload/) - Tiny, dependency-free async JavaScript and CSS loader.
* <code>&nbsp;&nbsp;2906</code> ![](https://img.shields.io/github/last-commit/ded/script.js) [script.js](https://github.com/ded/script.js) - Asynchronous JavaScript loader and dependency manager.
* <code>&nbsp;12061</code> ![](https://img.shields.io/github/last-commit/systemjs/systemjs) [systemjs](https://github.com/systemjs/systemjs) - AMD, CJS & ES6 spec-compliant module loader.
* <code>&nbsp;&nbsp;&nbsp;296</code> ![](https://img.shields.io/github/last-commit/yanhaijing/lodjs) [LodJS](https://github.com/yanhaijing/lodjs) - Module loader based on AMD.
* <code>&nbsp;&nbsp;&nbsp;828</code> ![](https://img.shields.io/github/last-commit/ecomfe/esl) [ESL](https://github.com/ecomfe/esl) - Module loader browser first, support lazy define and AMD.
* <code>&nbsp;&nbsp;&nbsp;121</code> ![](https://img.shields.io/github/last-commit/lrsjng/modulejs) [modulejs](https://github.com/lrsjng/modulejs) - Lightweight JavaScript module system.


## Bundlers

* <code>&nbsp;60864</code> ![](https://img.shields.io/github/last-commit/webpack/webpack) [webpack](https://github.com/webpack/webpack) - Packs CommonJs/AMD modules for the browser.
* <code>&nbsp;21486</code> ![](https://img.shields.io/github/last-commit/rollup/rollup) [Rollup](https://github.com/rollup/rollup) - Next-generation ES6 module bundler.
* <code>&nbsp;&nbsp;6815</code> ![](https://img.shields.io/github/last-commit/brunch/brunch) [Brunch](https://github.com/brunch/brunch) - Fast front-end web app build tool with simple declarative config.
* <code>&nbsp;40575</code> ![](https://img.shields.io/github/last-commit/parcel-bundler/parcel) [Parcel](https://github.com/parcel-bundler/parcel) - Blazing fast, zero configuration web application bundler.
* <code>&nbsp;&nbsp;6897</code> ![](https://img.shields.io/github/last-commit/developit/microbundle) [Microbundle](https://github.com/developit/microbundle) - Zero-configuration bundler for tiny modules.
* <code>&nbsp;&nbsp;4053</code> ![](https://img.shields.io/github/last-commit/fuse-box/fuse-box) [FuseBox](https://github.com/fuse-box/fuse-box) - A bundler that does it right
* [Snowpack](https://www.snowpack.dev/) - A lightning-fast frontend build tool, designed for the modern web.


## Type Checkers

* [TypeScript](https://www.typescriptlang.org/) - A typed superset of JavaScript that compiles to plain JavaScript.
* [Flow.js](https://flow.org/en/) - A static type checker for JavaScript from Facebook.
* [Hegel](https://hegel.js.org/) -  A static type checker for JavaScript with a bias on type inference an strong type system.
* <code>&nbsp;&nbsp;&nbsp;332</code> ![](https://img.shields.io/github/last-commit/getify/TypL) [TypL](https://github.com/getify/TypL) - the JavaScript Type Linter with a bias on type inference.
* <code>&nbsp;&nbsp;&nbsp;183</code> ![](https://img.shields.io/github/last-commit/xodio/hm-def) [Hindley Milner Definitions](https://github.com/xodio/hm-def) - runtime type checking for JavaScript functions using Haskell-alike Hindley Milner type signatures.


## Testing Frameworks

### Frameworks

* <code>&nbsp;21292</code> ![](https://img.shields.io/github/last-commit/mochajs/mocha) [mocha](https://github.com/mochajs/mocha) - Simple, flexible, fun JavaScript test framework for node.js & the browser.
* <code>&nbsp;15320</code> ![](https://img.shields.io/github/last-commit/jasmine/jasmine) [jasmine](https://github.com/jasmine/jasmine) - DOM-less simple JavaScript testing framework.
* <code>&nbsp;&nbsp;3948</code> ![](https://img.shields.io/github/last-commit/jquery/qunit) [qunit](https://github.com/jquery/qunit) - An easy-to-use JavaScript Unit Testing framework.
* <code>&nbsp;38616</code> ![](https://img.shields.io/github/last-commit/facebook/jest) [jest](https://github.com/facebook/jest) - Painless JavaScript Unit Testing.
* <code>&nbsp;&nbsp;&nbsp;334</code> ![](https://img.shields.io/github/last-commit/azer/prova) [prova](https://github.com/azer/prova) - Node & Browser test runner based on Tape and Browserify
* <code>&nbsp;&nbsp;&nbsp;703</code> ![](https://img.shields.io/github/last-commit/dalekjs/dalek) [DalekJS](https://github.com/dalekjs/dalek) - Automated cross browser functional testing with JavaScript
* <code>&nbsp;&nbsp;8788</code> ![](https://img.shields.io/github/last-commit/angular/protractor) [Protractor](https://github.com/angular/protractor) - Protractor is an end-to-end test framework for AngularJS applications.
* <code>&nbsp;&nbsp;5607</code> ![](https://img.shields.io/github/last-commit/substack/tape) [tape](https://github.com/substack/tape) - Tap-producing test harness for node and browsers.
* <code>&nbsp;&nbsp;9302</code> ![](https://img.shields.io/github/last-commit/DevExpress/testcafe) [TestCafe](https://github.com/DevExpress/testcafe) - Automated browser testing for the modern web development stack.
* <code>&nbsp;19740</code> ![](https://img.shields.io/github/last-commit/avajs/ava) [ava](https://github.com/avajs/ava) - 🚀 Futuristic JavaScript test runner
* [Cypress](https://www.cypress.io/) - Complete end-to-end testing framework for anything that runs in a browser and beyond.

### Assertion

* <code>&nbsp;&nbsp;7538</code> ![](https://img.shields.io/github/last-commit/chaijs/chai) [chai](https://github.com/chaijs/chai) - BDD / TDD assertion framework for node.js and the browser that can be paired with any testing framework.
* [Enzyme](https://airbnb.io/enzyme/index.html) - Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output.
* <code>&nbsp;16250</code> ![](https://img.shields.io/github/last-commit/kentcdodds/react-testing-library) [react testing library](https://github.com/kentcdodds/react-testing-library) - Simple and complete React DOM testing utilities that encourage good testing practices.
* <code>&nbsp;&nbsp;8953</code> ![](https://img.shields.io/github/last-commit/sinonjs/sinon) [Sinon.JS](https://github.com/sinonjs/sinon) - Test spies, stubs, and mocks for JavaScript.
* <code>&nbsp;&nbsp;2101</code> ![](https://img.shields.io/github/last-commit/Automattic/expect.js) [expect.js](https://github.com/Automattic/expect.js) - Minimalistic BDD-style assertions for Node.JS and the browser.
* <code>&nbsp;&nbsp;2679</code> ![](https://img.shields.io/github/last-commit/thlorenz/proxyquire) [proxyquire](https://github.com/thlorenz/proxyquire) - Stub nodejs's require.

### Coverage

* <code>&nbsp;&nbsp;8508</code> ![](https://img.shields.io/github/last-commit/gotwarlost/istanbul) [istanbul](https://github.com/gotwarlost/istanbul) - Yet another JS code coverage tool.
* <code>&nbsp;&nbsp;1414</code> ![](https://img.shields.io/github/last-commit/alex-seville/blanket) [blanket](https://github.com/alex-seville/blanket) - A simple code coverage library for JavaScript. Designed to be easy to install and use, for both browser and nodejs.
* <code>&nbsp;&nbsp;&nbsp;388</code> ![](https://img.shields.io/github/last-commit/tntim96/JSCover) [JSCover](https://github.com/tntim96/JSCover) - JSCover is a tool that measures code coverage for JavaScript programs.

### Runner

* <code>&nbsp;28796</code> ![](https://img.shields.io/github/last-commit/ariya/phantomjs) [phantomjs](https://github.com/ariya/phantomjs) - Scriptable Headless WebKit.
* <code>&nbsp;&nbsp;2975</code> ![](https://img.shields.io/github/last-commit/laurentj/slimerjs) [slimerjs](https://github.com/laurentj/slimerjs) - A PhantomJS-like tool running Gecko.
* <code>&nbsp;&nbsp;7277</code> ![](https://img.shields.io/github/last-commit/casperjs/casperjs) [casperjs](https://github.com/casperjs/casperjs) - Navigation scripting & testing utility for PhantomJS and SlimerJS.
* <code>&nbsp;&nbsp;5598</code> ![](https://img.shields.io/github/last-commit/assaf/zombie) [zombie](https://github.com/assaf/zombie) - Insanely fast, full-stack, headless browser testing using node.js.
* <code>&nbsp;&nbsp;&nbsp;568</code> ![](https://img.shields.io/github/last-commit/totorojs/totoro) [totoro](https://github.com/totorojs/totoro) - A simple and stable cross-browser testing tool.
* <code>&nbsp;11658</code> ![](https://img.shields.io/github/last-commit/karma-runner/karma) [karma](https://github.com/karma-runner/karma) - Spectacular Test Runner for JavaScript.
* <code>&nbsp;11051</code> ![](https://img.shields.io/github/last-commit/nightwatchjs/nightwatch) [nightwatch](https://github.com/nightwatchjs/nightwatch) - UI automated testing framework based on node.js and selenium webdriver.
* <code>&nbsp;&nbsp;4342</code> ![](https://img.shields.io/github/last-commit/theintern/intern) [intern](https://github.com/theintern/intern) - A next-generation code testing stack for JavaScript.
* [yolpo](http://www.yolpo.com) - A statement-by-statement JavaScript interpreter in the browser.
* <code>&nbsp;77366</code> ![](https://img.shields.io/github/last-commit/GoogleChrome/puppeteer) [puppeteer](https://github.com/GoogleChrome/puppeteer) - Headless Chrome Node.js API by official Google Chrome team.
* <code>&nbsp;&nbsp;7474</code> ![](https://img.shields.io/github/last-commit/webdriverio/webdriverio) [webdriverio](https://github.com/webdriverio/webdriverio) - Next-gen WebDriver test automation framework for Node.js.
* <code>&nbsp;&nbsp;3127</code> ![](https://img.shields.io/github/last-commit/getgauge/taiko) [taiko](https://github.com/getgauge/taiko) - A Node.js library with a simple API to automate Chromium based browsers.
* <code>&nbsp;36649</code> ![](https://img.shields.io/github/last-commit/microsoft/playwright) [Playwright](https://github.com/microsoft/playwright) - Node.js library to automate Chromium, Firefox and WebKit with a single API.

## QA Tools

* <code>&nbsp;42425</code> ![](https://img.shields.io/github/last-commit/prettier/prettier) [prettier](https://github.com/prettier/prettier) - Prettier is an opinionated code formatter.
* <code>&nbsp;&nbsp;8720</code> ![](https://img.shields.io/github/last-commit/jshint/jshint) [JSHint](https://github.com/jshint/jshint/) - JSHint is a tool that helps to detect errors and potential problems in your JavaScript code.
* <code>&nbsp;&nbsp;5013</code> ![](https://img.shields.io/github/last-commit/jscs-dev/node-jscs) [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript Code Style checker.
* <code>&nbsp;&nbsp;1694</code> ![](https://img.shields.io/github/last-commit/rdio/jsfmt) [jsfmt](https://github.com/rdio/jsfmt) - For formatting, searching, and rewriting JavaScript.
* <code>&nbsp;&nbsp;3428</code> ![](https://img.shields.io/github/last-commit/danielstjules/jsinspect) [jsinspect](https://github.com/danielstjules/jsinspect) - Detect copy-pasted and structurally similar code.
* <code>&nbsp;&nbsp;&nbsp;802</code> ![](https://img.shields.io/github/last-commit/danielstjules/buddy.js) [buddy.js](https://github.com/danielstjules/buddy.js) - Magic number detection for JavaScript.
* <code>&nbsp;20377</code> ![](https://img.shields.io/github/last-commit/eslint/eslint) [ESLint](https://github.com/eslint/eslint) - A fully pluggable tool for identifying and reporting on patterns in JavaScript.
* <code>&nbsp;&nbsp;3494</code> ![](https://img.shields.io/github/last-commit/douglascrockford/JSLint) [JSLint](https://github.com/douglascrockford/JSLint) - High-standards, strict & opinionated code quality tool, aiming to keep only good parts of the language.
* <code>&nbsp;26882</code> ![](https://img.shields.io/github/last-commit/feross/standard) [JavaScript Standard Style](https://github.com/feross/standard) - Opinionated, no-configuration style guide, style checker, and formatter
* <code>&nbsp;&nbsp;&nbsp;110</code> ![](https://img.shields.io/github/last-commit/kentcdodds/preval.macro) [Pre-evaluate code at buildtime](https://github.com/kentcdodds/preval.macro) - Pre-evaluate your front end javascript code at build-time
* <code>&nbsp;&nbsp;7680</code> ![](https://img.shields.io/github/last-commit/beautify-web/js-beautify) [JS-Beautifier](https://github.com/beautify-web/js-beautify) - Npm cli and library to format JS code.
* <code>&nbsp;26170</code> ![](https://img.shields.io/github/last-commit/typicode/husky) [husky](https://github.com/typicode/husky) - Prevents bad git commit, git push and more.

## MVC Frameworks and Libraries

* <code>&nbsp;59484</code> ![](https://img.shields.io/github/last-commit/angular/angular.js) [angular.js](https://github.com/angular/angular.js) - HTML enhanced for web apps. (deprecated)
* <code>&nbsp;80789</code> ![](https://img.shields.io/github/last-commit/angular/angular) [angular](https://github.com/angular/angular) - Angular is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.
* [aurelia](http://aurelia.io) - A JavaScript client framework for mobile, desktop and web.
* <code>&nbsp;27866</code> ![](https://img.shields.io/github/last-commit/jashkenas/backbone) [backbone](https://github.com/jashkenas/backbone) - Give your JS App some Backbone with Models, Views, Collections, and Events.
* <code>&nbsp;22171</code> ![](https://img.shields.io/github/last-commit/emberjs/ember.js) [ember.js](https://github.com/emberjs/ember.js) - A JavaScript framework for creating ambitious web applications.
* <code>&nbsp;42867</code> ![](https://img.shields.io/github/last-commit/meteor/meteor) [meteor](https://github.com/meteor/meteor) - An ultra-simple, database-everywhere, data-on-the-wire, pure-javascript web framework.
* <code>&nbsp;&nbsp;5876</code> ![](https://img.shields.io/github/last-commit/ractivejs/ractive) [ractive](https://github.com/ractivejs/ractive) - Next-generation DOM manipulation.
* <code>195009</code> ![](https://img.shields.io/github/last-commit/vuejs/vue) [vue](https://github.com/vuejs/vue) - Intuitive, fast & composable MVVM for building interactive interfaces.
* <code>&nbsp;57424</code> ![](https://img.shields.io/github/last-commit/sveltejs/svelte) [svelte](https://github.com/sveltejs/svelte) - Svelte is a new way to build web applications. It's a compiler that takes your declarative components and converts them into efficient JavaScript that surgically updates the DOM.
* <code>&nbsp;10168</code> ![](https://img.shields.io/github/last-commit/knockout/knockout) [knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript.
* <code>&nbsp;&nbsp;3599</code> ![](https://img.shields.io/github/last-commit/spine/spine) [spine](https://github.com/spine/spine) - Lightweight MVC library for building JavaScript applications.
* <code>&nbsp;&nbsp;&nbsp;520</code> ![](https://img.shields.io/github/last-commit/techlayer/espresso.js) [espresso.js](https://github.com/techlayer/espresso.js) - A minimal JavaScript library for crafting user interfaces.
* <code>&nbsp;&nbsp;1890</code> ![](https://img.shields.io/github/last-commit/canjs/canjs) [canjs](https://github.com/canjs/canjs) - Can do JS, better, faster, easier.
* [react](https://reactjs.org/) - A library for building user interfaces. It's declarative, efficient, and extremely flexible. Works with a Virtual DOM.
* <code>&nbsp;18754</code> ![](https://img.shields.io/github/last-commit/hyperapp/hyperapp) [hyperapp](https://github.com/hyperapp/hyperapp) - 1kb JavaScript library for building frontend applications.
* <code>&nbsp;31497</code> ![](https://img.shields.io/github/last-commit/developit/preact) [preact](https://github.com/developit/preact) - Fast 3kb React alternative with the same ES6 API. Components & Virtual DOM.
* <code>&nbsp;21098</code> ![](https://img.shields.io/github/last-commit/NativeScript/NativeScript) [nativescript](https://github.com/NativeScript/NativeScript) - Build truly native cross-platform iOS and Android apps with JavaScript.
* <code>102169</code> ![](https://img.shields.io/github/last-commit/facebook/react-native) [react-native](https://github.com/facebook/react-native) - A framework for building native apps with React.
* <code>&nbsp;14650</code> ![](https://img.shields.io/github/last-commit/riot/riot) [riot](https://github.com/riot/riot) - React-like library, but with very small size.
* <code>&nbsp;&nbsp;1336</code> ![](https://img.shields.io/github/last-commit/walmartlabs/thorax) [thorax](https://github.com/walmartlabs/thorax) - Strengthening your Backbone.
* <code>&nbsp;&nbsp;2882</code> ![](https://img.shields.io/github/last-commit/chaplinjs/chaplin) [chaplin](https://github.com/chaplinjs/chaplin) - An architecture for JavaScript applications using the Backbone.js library.
* <code>&nbsp;&nbsp;7103</code> ![](https://img.shields.io/github/last-commit/marionettejs/backbone.marionette) [marionette](https://github.com/marionettejs/backbone.marionette) - A composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications.
* <code>&nbsp;&nbsp;1282</code> ![](https://img.shields.io/github/last-commit/ripplejs/ripple) [ripple](https://github.com/ripplejs/ripple) - A tiny foundation for building reactive views.
* <code>&nbsp;&nbsp;3223</code> ![](https://img.shields.io/github/last-commit/mikeric/rivets) [rivets](https://github.com/mikeric/rivets) - Lightweight and powerful data binding + templating solution.
* <code>&nbsp;&nbsp;4650</code> ![](https://img.shields.io/github/last-commit/derbyjs/derby) [derby](https://github.com/derbyjs/derby) - MVC framework making it easy to write realtime, collaborative applications that run in both Node.js and browsers.
    * <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/russll/awesome-derby) [derby-awesome](https://github.com/russll/awesome-derby) - A collection of awesome derby components
* <code>&nbsp;&nbsp;2893</code> ![](https://img.shields.io/github/last-commit/gwendall/way.js) [way.js](https://github.com/gwendall/way.js) - Simple, lightweight, persistent two-way databinding.
* <code>&nbsp;13174</code> ![](https://img.shields.io/github/last-commit/lhorie/mithril.js) [mithril.js](https://github.com/lhorie/mithril.js) - Mithril is a client-side MVC framework (Light-weight, Robust, Fast).
* <code>&nbsp;&nbsp;2789</code> ![](https://img.shields.io/github/last-commit/astoilkov/jsblocks) [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks is better MV-ish framework.
* [LiquidLava](http://www.lava-framework.com/) - Transparent MVC framework for building user interfaces.
* <code>&nbsp;13927</code> ![](https://img.shields.io/github/last-commit/feathersjs/feathers) [feathers](https://github.com/feathersjs/feathers) - A minimalist real-time JavaScript framework for tomorrow's apps.
* <code>&nbsp;&nbsp;&nbsp;223</code> ![](https://img.shields.io/github/last-commit/Wildhoney/Keo) [Keo](https://github.com/Wildhoney/Keo) - Functional stateless React components with Shadow DOM support.
* <code>&nbsp;&nbsp;&nbsp;280</code> ![](https://img.shields.io/github/last-commit/emadalam/atvjs) [atvjs](https://github.com/emadalam/atvjs) - Blazing fast Apple TV application development using pure JavaScript.
* <code>&nbsp;20381</code> ![](https://img.shields.io/github/last-commit/alpinejs/alpine) [Alpine.js](https://github.com/alpinejs/alpine) - offers you the reactive and declarative nature of big frameworks like Vue or React at a much lower cost.
* <code>&nbsp;15358</code> ![](https://img.shields.io/github/last-commit/infernojs/inferno) [inferno](https://github.com/infernojs/inferno) - 🔥 An extremely fast, React-like JavaScript library for building modern user interfaces.
* [FoalTS](https://foalts.org) - Elegant and all-inclusive Node.JS framework for building web applications (TypeScript).
* <code>&nbsp;&nbsp;&nbsp;636</code> ![](https://img.shields.io/github/last-commit/aidenybai/lucia) [Lucia](https://github.com/aidenybai/lucia) - 3kb library for tiny web apps.
* <code>&nbsp;12329</code> ![](https://img.shields.io/github/last-commit/adonisjs/core) [Adonis](https://github.com/adonisjs/core) - The Node.js Framework highly focused on developer ergonomics, stability and confidence.
* <code>&nbsp;15572</code> ![](https://img.shields.io/github/last-commit/artf/grapesjs) [GrapesJS](https://github.com/artf/grapesjs) - Free and Open source Web Builder Framework. Next generation tool for building templates without coding.
* <code>&nbsp;&nbsp;7439</code> ![](https://img.shields.io/github/last-commit/retejs/rete) [Rete.js](https://github.com/retejs/rete) - A modular framework for visual programming allows to create node based editor in browser.
* <code>&nbsp;&nbsp;2897</code> ![](https://img.shields.io/github/last-commit/jagenjo/litegraph.js) [litegraph.js](https://github.com/jagenjo/litegraph.js) - A graph node engine and editor similar to PD or UDK Blueprints, comes with its own editor in HTML5 Canvas2D.
* <code>&nbsp;&nbsp;1849</code> ![](https://img.shields.io/github/last-commit/jerosoler/Drawflow) [Drawflow](https://github.com/jerosoler/Drawflow) - This allow you to create data flows easily and quickly.
* <code>&nbsp;10187</code> ![](https://img.shields.io/github/last-commit/google/blockly) [Blockly](https://github.com/google/blockly) - A library that adds a visual code editor to web and mobile apps by Google.
* <code>&nbsp;&nbsp;1922</code> ![](https://img.shields.io/github/last-commit/aidenybai/million) [Million](https://github.com/aidenybai/million) - <1kb compiler-focused virtual DOM. It's fast!

## Node-Powered CMS Frameworks

* <code>&nbsp;&nbsp;6163</code> ![](https://img.shields.io/github/last-commit/keystonejs/keystone) [KeystoneJS](https://github.com/keystonejs/keystone) - powerful CMS and web app framework.
* <code>&nbsp;11707</code> ![](https://img.shields.io/github/last-commit/reactioncommerce/reaction) [Reaction Commerce](https://github.com/reactioncommerce/reaction) - reactive CMS, real-time architecture and design.
* <code>&nbsp;39918</code> ![](https://img.shields.io/github/last-commit/tryghost/Ghost) [Ghost](https://github.com/tryghost/Ghost) - simple, powerful publishing platform.
* <code>&nbsp;&nbsp;3810</code> ![](https://img.shields.io/github/last-commit/punkave/apostrophe) [Apostrophe](https://github.com/punkave/apostrophe) - CMS with content editing and essential services.
* <code>&nbsp;&nbsp;&nbsp;209</code> ![](https://img.shields.io/github/last-commit/wejs/we) [We.js](https://github.com/wejs/we/) - framework for real time apps, sites or blogs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;73</code> ![](https://img.shields.io/github/last-commit/inventures/hatchjs) [Hatch.js](https://github.com/inventures/hatchjs) - CMS platform with social features.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;17</code> ![](https://img.shields.io/github/last-commit/xtremespb/taracotjs-generator) [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) - fast and minimalist CMS based on Node.js.
* <code>&nbsp;&nbsp;&nbsp;176</code> ![](https://img.shields.io/github/last-commit/nodize/nodizecms) [Nodizecms](https://github.com/nodize/nodizecms) - CMS for CoffeeScript lovers.
* <code>&nbsp;&nbsp;&nbsp;666</code> ![](https://img.shields.io/github/last-commit/jcoppieters/cody) [Cody](https://github.com/jcoppieters/cody) - CMS with WSYWYG editor.
* <code>&nbsp;&nbsp;1588</code> ![](https://img.shields.io/github/last-commit/pencilblue/pencilblue) [PencilBlue](https://github.com/pencilblue/pencilblue/) - CMS and blogging platform.
* <code>&nbsp;44368</code> ![](https://img.shields.io/github/last-commit/strapi/strapi) [Strapi](https://github.com/strapi/strapi) - Open source Node.js Headless CMS to easily build customisable APIs.
* <code>&nbsp;&nbsp;1314</code> ![](https://img.shields.io/github/last-commit/fiction-com/factor) [Factor](https://github.com/fiction-com/factor) - The Javascript CMS

## Templating Engines
*Templating engines allow you to perform string interpolation.*

* <code>&nbsp;15254</code> ![](https://img.shields.io/github/last-commit/janl/mustache.js) [mustache.js](https://github.com/janl/mustache.js) - Minimal templating with {{mustaches}} in JavaScript.
* <code>&nbsp;16522</code> ![](https://img.shields.io/github/last-commit/handlebars-lang/handlebars.js) [handlebars.js](https://github.com/handlebars-lang/handlebars.js) - An extension to the Mustache templating language.
* [nunjucks](https://mozilla.github.io/nunjucks/) - A rich and powerful templating language for JavaScript from Mozilla.
* <code>&nbsp;&nbsp;5101</code> ![](https://img.shields.io/github/last-commit/twitter/hogan.js) [hogan.js](https://github.com/twitter/hogan.js) - A compiler for the Mustache templating language.
* <code>&nbsp;&nbsp;4793</code> ![](https://img.shields.io/github/last-commit/olado/doT) [doT](https://github.com/olado/doT) - The fastest + concise JavaScript template engine for nodejs and browsers.
* <code>&nbsp;&nbsp;2902</code> ![](https://img.shields.io/github/last-commit/linkedin/dustjs) [dustjs](https://github.com/linkedin/dustjs/) - Asynchronous templates for the browser and node.js.
* <code>&nbsp;&nbsp;1734</code> ![](https://img.shields.io/github/last-commit/sstephenson/eco) [eco](https://github.com/sstephenson/eco/) - Embedded CoffeeScript templates.
* <code>&nbsp;&nbsp;1677</code> ![](https://img.shields.io/github/last-commit/blueimp/JavaScript-Templates) [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - < 1KB lightweight, fast & powerful JavaScript templating engine with zero dependencies.
* <code>&nbsp;&nbsp;&nbsp;813</code> ![](https://img.shields.io/github/last-commit/jasonmoo/t.js) [t.js](https://github.com/jasonmoo/t.js) - A tiny JavaScript templating framework in ~400 bytes gzipped.
* <code>&nbsp;20701</code> ![](https://img.shields.io/github/last-commit/pugjs/pug) [Pug](https://github.com/pugjs/pug) - Robust, elegant, feature rich template engine for nodejs. (formerly known as Jade)
* <code>&nbsp;&nbsp;6230</code> ![](https://img.shields.io/github/last-commit/mde/ejs) [EJS](https://github.com/mde/ejs) - Effective JavaScript templating.
* <code>&nbsp;&nbsp;&nbsp;548</code> ![](https://img.shields.io/github/last-commit/xtemplate/xtemplate) [xtemplate](https://github.com/xtemplate/xtemplate) - eXtensible Template Engine lib for node and the browser
* <code>&nbsp;11164</code> ![](https://img.shields.io/github/last-commit/marko-js/marko) [marko](https://github.com/marko-js/marko) - A fast, lightweight, HTML-based templating engine for Node.js and the browser with async, streaming, custom tags and CommonJS modules as compiled output.
* <code>&nbsp;&nbsp;3125</code> ![](https://img.shields.io/github/last-commit/paularmstrong/swig) [swig](https://github.com/paularmstrong/swig) - (Archived) A simple, powerful, and extendable Node.js and browser-based JavaScript template engine.

## Articles and Posts

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-voc%C3%AA-deveria-conhecer-b70e94d1d706) - Article about concepts of JavaScript Functional.
* [How JavaScript works](https://blog.sessionstack.com/tagged/tutorial) - A series of articles about the building blocks of JavaScript.
* [Multi-threading using web-workers](https://www.loginradius.com/blog/async/adding-multi-threading-to-javascript-using-web-workers/) - Web Workers: Adding Multi-threading to JavaScript
* [this keyword in JavaScript](https://www.loginradius.com/blog/async/breaking-down-this-keyword-in-javascript/) - Breaking down the 'this' keyword in JavaScript

## Data Visualization
*Data visualization tools for the web.*

* <code>100960</code> ![](https://img.shields.io/github/last-commit/d3/d3) [d3](https://github.com/d3/d3) - A JavaScript visualization library for HTML and SVG.
* <code>&nbsp;&nbsp;7449</code> ![](https://img.shields.io/github/last-commit/mozilla/metrics-graphics) [metrics-graphics](https://github.com/mozilla/metrics-graphics) - A library optimized for concise, principled data graphics and layouts.
* <code>&nbsp;81043</code> ![](https://img.shields.io/github/last-commit/mrdoob/three.js) [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D library.
* <code>&nbsp;56671</code> ![](https://img.shields.io/github/last-commit/chartjs/Chart.js) [Chart.js](https://github.com/chartjs/Chart.js) - Simple HTML5 Charts using the &lt;canvas&gt; tag.
* <code>&nbsp;13087</code> ![](https://img.shields.io/github/last-commit/paperjs/paper.js) [paper.js](https://github.com/paperjs/paper.js) - The Swiss Army Knife of Vector Graphics Scripting – Scriptographer ported to JavaScript and the browser, using HTML5 Canvas.
* <code>&nbsp;21503</code> ![](https://img.shields.io/github/last-commit/kangax/fabric.js) [fabric.js](https://github.com/kangax/fabric.js) - JavaScript Canvas Library, SVG-to-Canvas (& canvas-to-SVG) Parser.
* <code>&nbsp;&nbsp;4213</code> ![](https://img.shields.io/github/last-commit/benpickles/peity) [peity](https://github.com/benpickles/peity) - Progressive <svg> bar, line and pie charts.
* <code>&nbsp;11051</code> ![](https://img.shields.io/github/last-commit/DmitryBaranovskiy/raphael) [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript Vector Library.
* <code>&nbsp;50636</code> ![](https://img.shields.io/github/last-commit/apache/echarts) [echarts](https://github.com/apache/echarts) - Enterprise Charts.
* [visjs](https://github.com/visjs) - Multiple Libraries for dynamic, browser-based data visualization.
* <code>&nbsp;&nbsp;7642</code> ![](https://img.shields.io/github/last-commit/jonobr1/two.js) [two.js](https://github.com/jonobr1/two.js) - A renderer agnostic two-dimensional drawing api for the web.
* <code>&nbsp;&nbsp;1517</code> ![](https://img.shields.io/github/last-commit/DmitryBaranovskiy/g.raphael) [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) - Charts for Raphaël.
* <code>&nbsp;&nbsp;9844</code> ![](https://img.shields.io/github/last-commit/jacomyal/sigma.js) [sigma.js](https://github.com/jacomyal/sigma.js) - A JavaScript library dedicated to graph drawing.
* <code>&nbsp;&nbsp;2589</code> ![](https://img.shields.io/github/last-commit/samizdatco/arbor) [arbor](https://github.com/samizdatco/arbor) - A graph visualization library using web workers and jQuery.
* <code>&nbsp;&nbsp;4910</code> ![](https://img.shields.io/github/last-commit/square/cubism) [cubism](https://github.com/square/cubism) - A D3 plugin for visualizing time series.
* <code>&nbsp;&nbsp;7312</code> ![](https://img.shields.io/github/last-commit/dc-js/dc.js) [dc.js](https://github.com/dc-js/dc.js) - Multi-Dimensional charting built to work natively with crossfilter rendered with d3.js
* <code>&nbsp;&nbsp;&nbsp;&nbsp;28</code> ![](https://img.shields.io/github/last-commit/trifacta/vega) [vega](https://github.com/trifacta/vega) - A visualization grammar.
* [processing.js](http://processingjs.org/) - Processing.js makes your data visualizations work using web standards and without any plug-ins.
* <code>&nbsp;&nbsp;1568</code> ![](https://img.shields.io/github/last-commit/HumbleSoftware/envisionjs) [envisionjs](https://github.com/HumbleSoftware/envisionjs) - Dynamic HTML5 visualization.
* <code>&nbsp;&nbsp;6516</code> ![](https://img.shields.io/github/last-commit/shutterstock/rickshaw) [rickshaw](https://github.com/shutterstock/rickshaw) - JavaScript toolkit for creating interactive real-time graphs.
* <code>&nbsp;&nbsp;5929</code> ![](https://img.shields.io/github/last-commit/flot/flot) [flot](https://github.com/flot/flot) - Attractive JavaScript charts for jQuery.
* <code>&nbsp;&nbsp;6968</code> ![](https://img.shields.io/github/last-commit/morrisjs/morris.js) [morris.js](https://github.com/morrisjs/morris.js) - Pretty time-series line graphs.
* <code>&nbsp;&nbsp;7147</code> ![](https://img.shields.io/github/last-commit/novus/nvd3) [nvd3](https://github.com/novus/nvd3) - Build re-usable charts and chart components for d3.js.
* <code>&nbsp;&nbsp;9563</code> ![](https://img.shields.io/github/last-commit/wout/svg.js) [svg.js](https://github.com/wout/svg.js) - A lightweight library for manipulating and animating SVG.
* <code>&nbsp;&nbsp;5747</code> ![](https://img.shields.io/github/last-commit/pa7/heatmap.js) [heatmap.js](https://github.com/pa7/heatmap.js) - JavaScript Library for HTML5 canvas based heatmaps.
* <code>&nbsp;&nbsp;1232</code> ![](https://img.shields.io/github/last-commit/gwatts/jquery.sparkline) [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - A plugin for the jQuery JavaScript library to generate small sparkline charts directly in the browser.
* <code>&nbsp;&nbsp;9874</code> ![](https://img.shields.io/github/last-commit/qrohlf/trianglify) [trianglify](https://github.com/qrohlf/trianglify) - Low poly style background generator with d3.js.
* <code>&nbsp;&nbsp;3530</code> ![](https://img.shields.io/github/last-commit/jasondavies/d3-cloud) [d3-cloud](https://github.com/jasondavies/d3-cloud) - Create word clouds in JavaScript.
* <code>&nbsp;&nbsp;&nbsp;429</code> ![](https://img.shields.io/github/last-commit/heavysixer/d4) [d4](https://github.com/heavysixer/d4) - A friendly reusable charts DSL for D3.
* [dimple.js](http://dimplejs.org) - Easy charts for business analytics powered by d3.
* <code>&nbsp;12793</code> ![](https://img.shields.io/github/last-commit/gionkunz/chartist-js) [chartist-js](https://github.com/gionkunz/chartist-js) - Simple responsive charts.
* <code>&nbsp;&nbsp;5010</code> ![](https://img.shields.io/github/last-commit/epochjs/epoch) [epoch](https://github.com/epochjs/epoch) - A general purpose real-time charting library.
* <code>&nbsp;&nbsp;9184</code> ![](https://img.shields.io/github/last-commit/c3js/c3) [c3](https://github.com/c3js/c3) - D3-based reusable chart library.
* <code>&nbsp;16526</code> ![](https://img.shields.io/github/last-commit/BabylonJS/Babylon.js) [BabylonJS](https://github.com/BabylonJS/Babylon.js) - A framework for building 3D games with HTML 5 and WebGL.
* <code>&nbsp;18048</code> ![](https://img.shields.io/github/last-commit/recharts/recharts) [recharts](https://github.com/recharts/recharts) - Redefined chart library built with React and D3.
* <code>&nbsp;&nbsp;&nbsp;952</code> ![](https://img.shields.io/github/last-commit/AnyChart/GraphicsJS) [GraphicsJS](https://github.com/AnyChart/GraphicsJS) - A lightweight JavaScript graphics library with the intuitive API, based on SVG/VML technology.
* <code>&nbsp;&nbsp;6339</code> ![](https://img.shields.io/github/last-commit/jgraph/mxgraph) [mxGraph](https://github.com/jgraph/mxgraph) - Diagramming library that enables interactive graph and charting applications to be quickly created that run natively in any major browser that is supported by its vendor.
* <code>&nbsp;14291</code> ![](https://img.shields.io/github/last-commit/frappe/charts) [Frappe Charts](https://github.com/frappe/charts) - GitHub-inspired simple and modern SVG charts for the web with zero dependencies.
* <code>&nbsp;&nbsp;2790</code> ![](https://img.shields.io/github/last-commit/frappe/gantt) [Frappe Gantt](https://github.com/frappe/gantt) - A simple, interactive, modern gantt chart library for the web.
* <code>&nbsp;11160</code> ![](https://img.shields.io/github/last-commit/antvis/G2) [G2](https://github.com/antvis/G2) - A highly interactive data-driven visualization grammar for statistical charts.
* <code>&nbsp;&nbsp;2180</code> ![](https://img.shields.io/github/last-commit/antvis/G2Plot) [G2Plot](https://github.com/antvis/G2Plot) - An interactive and responsive charting library. Based on the grammar of graphics.
* <code>&nbsp;&nbsp;8331</code> ![](https://img.shields.io/github/last-commit/cytoscape/cytoscape.js) [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - A fully featured graph theory library.
* [cola.js](https://ialab.it.monash.edu/webcola/) - library for arranging your HTML5 documents and diagrams using constraint-based optimization techniques
* <code>&nbsp;&nbsp;3564</code> ![](https://img.shields.io/github/last-commit/clientIO/joint) [jointjs](https://github.com/clientIO/joint) - Diagramming library to create static diagrams or fully interactive diagramming tools.
* <code>&nbsp;&nbsp;1469</code> ![](https://img.shields.io/github/last-commit/vizzuhq/vizzu-lib) [vizzu](https://github.com/vizzuhq/vizzu-lib) - Library for animated data visualizations and data stories.
 
There're also some great commercial libraries, like [amchart](https://www.amcharts.com/), [anychart](https://www.anychart.com/), [plotly](https://plotly.com/), [highchart](https://www.highcharts.com/), and [lightning chart](https://www.arction.com/lightningchart-js/).

## Timeline

* <code>&nbsp;&nbsp;2436</code> ![](https://img.shields.io/github/last-commit/NUKnightLab/TimelineJS3) [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) - A Storytelling Timeline built in JavaScript.
* <code>&nbsp;&nbsp;6885</code> ![](https://img.shields.io/github/last-commit/sbstjn/timesheet.js) [timesheet.js](https://github.com/sbstjn/timesheet.js) - JavaScript library for simple HTML5 & CSS3 time sheets.

## Spreadsheet

* <code>&nbsp;16491</code> ![](https://img.shields.io/github/last-commit/handsontable/handsontable) [HANDSONTABLE](https://github.com/handsontable/handsontable) - Handsontable is a JavaScript/HTML5 Spreadsheet Library for Developers
* <code>&nbsp;&nbsp;&nbsp;767</code> ![](https://img.shields.io/github/last-commit/frappe/datatable) [Frappe Datatable](https://github.com/frappe/datatable) - Frappe DataTable is a simple, modern and interactive datatable library for displaying tabular data. 
* <code>&nbsp;10727</code> ![](https://img.shields.io/github/last-commit/mengshukeji/Luckysheet) [Luckysheet](https://github.com/mengshukeji/Luckysheet) - Luckysheet is an online spreadsheet like excel that is powerful, simple to configure, and completely open source.

## Editors

* <code>&nbsp;24299</code> ![](https://img.shields.io/github/last-commit/ajaxorg/ace) [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 Editor).
* <code>&nbsp;24755</code> ![](https://img.shields.io/github/last-commit/codemirror/CodeMirror) [CodeMirror](https://github.com/codemirror/CodeMirror) - In-browser code editor.
* <code>&nbsp;&nbsp;&nbsp;387</code> ![](https://img.shields.io/github/last-commit/ariya/esprima) [esprima](https://github.com/ariya/esprima) - ECMAScript parsing infrastructure for multipurpose analysis.
* <code>&nbsp;32426</code> ![](https://img.shields.io/github/last-commit/quilljs/quill) [quill](https://github.com/quilljs/quill) - A cross browser rich text editor with an API.
* <code>&nbsp;15521</code> ![](https://img.shields.io/github/last-commit/yabwe/medium-editor) [medium-editor](https://github.com/yabwe/medium-editor) - Medium.com WYSIWYG editor clone.
* <code>&nbsp;&nbsp;4742</code> ![](https://img.shields.io/github/last-commit/sofish/pen) [pen](https://github.com/sofish/pen) - enjoy live editing (+markdown).
* <code>&nbsp;&nbsp;1694</code> ![](https://img.shields.io/github/last-commit/raphaelcruzeiro/jquery-notebook) [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - A simple, clean and elegant text editor. Inspired by the awesomeness of Medium.
* <code>&nbsp;&nbsp;5604</code> ![](https://img.shields.io/github/last-commit/mindmup/bootstrap-wysiwyg) [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - Tiny bootstrap-compatible WYSIWYG rich text editor.
* <code>&nbsp;&nbsp;&nbsp;518</code> ![](https://img.shields.io/github/last-commit/ckeditor/ckeditor-releases) [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - The best web text editor for everyone.
* <code>&nbsp;&nbsp;2754</code> ![](https://img.shields.io/github/last-commit/lepture/editor) [editor](https://github.com/lepture/editor) - A markdown editor. still on development.
* <code>&nbsp;&nbsp;4290</code> ![](https://img.shields.io/github/last-commit/OscarGodson/EpicEditor) [EpicEditor](https://github.com/OscarGodson/EpicEditor) - An embeddable JavaScript Markdown editor with split fullscreen editing, live previewing, automatic draft saving, offline support, and more.
* <code>&nbsp;&nbsp;9516</code> ![](https://img.shields.io/github/last-commit/josdejong/jsoneditor) [jsoneditor](https://github.com/josdejong/jsoneditor) - A web-based tool to view, edit and format JSON.
* <code>&nbsp;&nbsp;4447</code> ![](https://img.shields.io/github/last-commit/coolwanglu/vim.js) [vim.js](https://github.com/coolwanglu/vim.js) - JavaScript port of Vim with a persistent `~/.vimrc`.
* <code>&nbsp;&nbsp;4363</code> ![](https://img.shields.io/github/last-commit/neilj/Squire) [Squire](https://github.com/neilj/Squire) - HTML5 rich text editor.
* <code>&nbsp;11157</code> ![](https://img.shields.io/github/last-commit/tinymce/tinymce) [TinyMCE](https://github.com/tinymce/tinymce) - The JavaScript Rich Text editor.
* <code>&nbsp;16754</code> ![](https://img.shields.io/github/last-commit/basecamp/trix) [trix](https://github.com/basecamp/trix) - A rich text editor for everyday writing. By Basecamp.
* <code>&nbsp;&nbsp;3694</code> ![](https://img.shields.io/github/last-commit/Alex-D/Trumbowyg) [Trumbowyg](https://github.com/Alex-D/Trumbowyg) - A lightweight and amazing WYSIWYG JavaScript editor.
* <code>&nbsp;21619</code> ![](https://img.shields.io/github/last-commit/facebook/draft-js) [Draft.js](https://github.com/facebook/draft-js) - A React framework for building text editors.
* <code>&nbsp;&nbsp;4175</code> ![](https://img.shields.io/github/last-commit/jhollingworth/bootstrap-wysihtml5) [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) - Simple, beautiful wysiwyg editor
* <code>&nbsp;&nbsp;6544</code> ![](https://img.shields.io/github/last-commit/xing/wysihtml5) [wysihtml5](https://github.com/xing/wysihtml5) - Open source rich text editor based on HTML5 and the progressive-enhancement approach. Uses a sophisticated security concept and aims to generate fully valid HTML5 markup by preventing unmaintainable tag soups and inline styles.
* <code>&nbsp;&nbsp;&nbsp;530</code> ![](https://img.shields.io/github/last-commit/PANmedia/raptor-editor) [raptor-editor](https://github.com/PANmedia/raptor-editor) - Raptor, an HTML5 WYSIWYG content editor!
* <code>&nbsp;&nbsp;1048</code> ![](https://img.shields.io/github/last-commit/kenshin54/popline) [popline](https://github.com/kenshin54/popline) - Popline is an HTML5 Rich-Text-Editor Toolbar.
* <code>&nbsp;10697</code> ![](https://img.shields.io/github/last-commit/summernote/summernote) [Summernote](https://github.com/summernote/summernote) - Super simple WYSIWYG editor.


## Documentation

* [DevDocs](https://devdocs.io/) is an all-in-one API documentation reader with a fast, organized, and consistent interface.
* [dexy](http://www.dexy.it/) is a free-form literate documentation tool for writing any kind of technical document incorporating code.
* [docco](http://ashkenas.com/docco/) is a quick-and-dirty, hundred-line-long, literate-programming-style documentation generator.
* [styledocco](http://jacobrask.github.io/styledocco/) generates documentation and style guide documents from your stylesheets.
* <code>&nbsp;&nbsp;1290</code> ![](https://img.shields.io/github/last-commit/rtomayko/ronn) [Ronn](https://github.com/rtomayko/ronn) builds manuals. It converts simple, human readable textfiles to roff for terminal display, and also to HTML for the web.
* <code>&nbsp;&nbsp;2141</code> ![](https://img.shields.io/github/last-commit/tj/dox) [dox](https://github.com/tj/dox) is a JavaScript documentation generator written with node. Dox no longer generates an opinionated structure or style for your docs, it simply gives you a JSON representation, allowing you to use markdown and JSDoc-style tags.
* <code>&nbsp;&nbsp;&nbsp;207</code> ![](https://img.shields.io/github/last-commit/sutoiku/jsdox) [jsdox](https://github.com/sutoiku/jsdox) is a JSDoc3 to Markdown documentation generator.
* <code>&nbsp;&nbsp;2720</code> ![](https://img.shields.io/github/last-commit/esdoc/esdoc) [ESDoc](https://github.com/esdoc/esdoc) is a good documentation generator for JavaScript.
* [YUIDoc](http://yui.github.io/yuidoc/) is a Node.js application that generates API documentation from comments in source, using a syntax similar to tools like Javadoc and Doxygen.
* [coddoc](http://doug-martin.github.io/coddoc/) is a jsdoc parsing library. Coddoc is different in that it is easily extensible by allowing users to add tag and code parsers through the use of coddoc.addTagHandler and coddoc.addCodeHandler. coddoc also parses source code to be used in APIs.
* [sphinx](http://www.sphinx-doc.org/) a tool that makes it easy to create intelligent and beautiful documentation
* [Using JSDoc](http://usejsdoc.org/)
* <code>&nbsp;&nbsp;&nbsp;298</code> ![](https://img.shields.io/github/last-commit/beautiful-docs/beautiful-docs) [Beautiful docs](https://github.com/beautiful-docs/beautiful-docs) is a documentation viewer based on markdown files.
* [documentation.js](http://documentation.js.org) - API documentation generator with support for ES2015+ and flow annotation.
* <code>&nbsp;&nbsp;1508</code> ![](https://img.shields.io/github/last-commit/senchalabs/jsduck) [jsduck](https://github.com/senchalabs/jsduck) - API documentation generator made for Sencha JavaScript frameworks, but can be used for other frameworks too.
* <code>&nbsp;&nbsp;2605</code> ![](https://img.shields.io/github/last-commit/Bogdan-Lyashenko/codecrumbs) [codecrumbs](https://github.com/Bogdan-Lyashenko/codecrumbs) is a visual tool for learning and documenting a codebase by putting breadcrumbs in source code.


## Files
*Libraries for working with files.*

* <code>&nbsp;10469</code> ![](https://img.shields.io/github/last-commit/mholt/PapaParse) [Papa Parse](https://github.com/mholt/PapaParse) - A powerful CSV library that supports parsing CSV files/strings and also exporting to CSV.
* <code>&nbsp;&nbsp;&nbsp;518</code> ![](https://img.shields.io/github/last-commit/jDataView/jBinary) [jBinary](https://github.com/jDataView/jBinary) - High-level I/O (loading, parsing, manipulating, serializing, saving) for binary files with declarative syntax for describing file types and data structures.
* <code>&nbsp;&nbsp;2017</code> ![](https://img.shields.io/github/last-commit/rtfpessoa/diff2html) [diff2html](https://github.com/rtfpessoa/diff2html) - Git diff output parser and pretty HTML generator.
* <code>&nbsp;24143</code> ![](https://img.shields.io/github/last-commit/MrRio/jsPDF) [jsPDF](https://github.com/MrRio/jsPDF) - JavaScript PDF generation.
* <code>&nbsp;38218</code> ![](https://img.shields.io/github/last-commit/mozilla/pdf.js) [PDF.js](https://github.com/mozilla/pdf.js) - PDF Reader in JavaScript.


## Functional Programming
*Functional programming libraries to extend JavaScript’s capabilities.*

* <code>&nbsp;26390</code> ![](https://img.shields.io/github/last-commit/jashkenas/underscore) [underscore](https://github.com/jashkenas/underscore) - JavaScript's utility _ belt.
* <code>&nbsp;52938</code> ![](https://img.shields.io/github/last-commit/lodash/lodash) [lodash](https://github.com/lodash/lodash) - A utility library delivering consistency, customization, performance, & extras.
* <code>&nbsp;&nbsp;4475</code> ![](https://img.shields.io/github/last-commit/andrewplummer/Sugar) [Sugar](https://github.com/andrewplummer/Sugar) - A JavaScript library for working with native objects.
* <code>&nbsp;&nbsp;5998</code> ![](https://img.shields.io/github/last-commit/dtao/lazy.js) [lazy.js](https://github.com/dtao/lazy.js) - Like Underscore, but lazier.
* [ramda](https://github.com/CrossEye/ramda) - A practical functional library for JavaScript programmers.
* <code>&nbsp;&nbsp;1247</code> ![](https://img.shields.io/github/last-commit/mout/mout) [mout](https://github.com/mout/mout) - Modular JavaScript Utilities.
* <code>&nbsp;&nbsp;1015</code> ![](https://img.shields.io/github/last-commit/crcn/mesh.js) [mesh](https://github.com/crcn/mesh.js) - Streamable data synchronization utility.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;92</code> ![](https://img.shields.io/github/last-commit/alanrsoares/prelude-js) [preludejs](https://github.com/alanrsoares/prelude-js) - Hardcore Functional Programming for JavaScript.
* <code>&nbsp;&nbsp;1281</code> ![](https://img.shields.io/github/last-commit/selfrefactor/rambda) [rambda](https://github.com/selfrefactor/rambda) - Faster and smaller alternative to *Ramda*.
* <code>&nbsp;&nbsp;&nbsp;416</code> ![](https://img.shields.io/github/last-commit/marpple/FxTS) [fxts](https://github.com/marpple/FxTS) - Lazy evaluation and concurrency.


## Reactive Programming
*Reactive programming libraries to extend JavaScript’s capabilities.*

* <code>&nbsp;26862</code> ![](https://img.shields.io/github/last-commit/ReactiveX/rxjs) [RxJS](https://github.com/ReactiveX/rxjs) - A reactive programming library for JavaScript.
* <code>&nbsp;&nbsp;6404</code> ![](https://img.shields.io/github/last-commit/baconjs/bacon.js) [Bacon](https://github.com/baconjs/bacon.js) - FRP (functional reactive programming) library for JavaScript.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7</code> ![](https://img.shields.io/github/last-commit/pozadi/kefir) [Kefir](https://github.com/pozadi/kefir) - FRP library for JavaScript inspired by Bacon.js and RxJS with focus on high performance and low memory consumption.
* [Highland](https://caolan.github.io/highland/) - Re-thinking the JavaScript utility belt, Highland manages synchronous and asynchronous code easily, using nothing more than standard JavaScript and Node-like Streams.
* <code>&nbsp;&nbsp;3428</code> ![](https://img.shields.io/github/last-commit/cujojs/most) [Most.js](https://github.com/cujojs/most) - high performance FRP library.
* <code>&nbsp;25099</code> ![](https://img.shields.io/github/last-commit/mobxjs/mobx) [MobX](https://github.com/mobxjs/mobx) - TFRP library for simple, scalable state management.
* [Cycle.js](https://cycle.js.org) - A functional and reactive JavaScript library for cleaner code.
* <code>&nbsp;&nbsp;1082</code> ![](https://img.shields.io/github/last-commit/concentjs/concent) [concent](https://github.com/concentjs/concent) - Definitely the ❤️ simplest but ⚡️ strongest state management for react, it is predictable、progressive and efficient.

## Data Structure
*Data structure libraries to build a more sophisticated application.*

* <code>&nbsp;31902</code> ![](https://img.shields.io/github/last-commit/facebook/immutable-js) [immutable-js](https://github.com/facebook/immutable-js) - Immutable Data Collections including Sequence, Range, Repeat, Map, OrderedMap, Set and a sparse Vector.
* <code>&nbsp;&nbsp;3356</code> ![](https://img.shields.io/github/last-commit/swannodette/mori) [mori](https://github.com/swannodette/mori) - A library for using ClojureScript's persistent data structures and supporting API from the comfort of vanilla JavaScript.
* <code>&nbsp;&nbsp;1190</code> ![](https://img.shields.io/github/last-commit/mauriciosantos/Buckets-JS) [buckets](https://github.com/mauriciosantos/Buckets-JS) - A complete, fully tested and documented data structure library written in JavaScript.
* <code>&nbsp;&nbsp;&nbsp;374</code> ![](https://img.shields.io/github/last-commit/flesler/hashmap) [hashmap](https://github.com/flesler/hashmap) - Simple hashmap implementation that supports any kind of keys.
* <code>&nbsp;&nbsp;&nbsp;366</code> ![](https://img.shields.io/github/last-commit/anvaka/ngraph.graph) [ngraph.graph](https://github.com/anvaka/ngraph.graph) - Graph data structure in javascript.


## Date
*Date Libraries.*

* <code>&nbsp;46467</code> ![](https://img.shields.io/github/last-commit/moment/moment) [moment](https://github.com/moment/moment) - Parse, validate, manipulate, and display dates in JavaScript.
* <code>&nbsp;&nbsp;3660</code> ![](https://img.shields.io/github/last-commit/moment/moment-timezone) [moment-timezone](https://github.com/moment/moment-timezone) - Timezone support for moment.js.
* <code>&nbsp;&nbsp;3815</code> ![](https://img.shields.io/github/last-commit/rmm5t/jquery-timeago) [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - A jQuery plugin that makes it easy to support automatically updating fuzzy timestamps (e.g. "4 minutes ago").
* <code>&nbsp;&nbsp;&nbsp;828</code> ![](https://img.shields.io/github/last-commit/mde/timezone-js) [timezone-js](https://github.com/mde/timezone-js) - Timezone-enabled JavaScript Date object. Uses Olson zoneinfo files for timezone data.
* <code>&nbsp;&nbsp;1464</code> ![](https://img.shields.io/github/last-commit/MatthewMueller/date) [date](https://github.com/MatthewMueller/date) - Date() for humans.
* <code>&nbsp;&nbsp;3930</code> ![](https://img.shields.io/github/last-commit/rauchg/ms.js) [ms.js](https://github.com/rauchg/ms.js) - Tiny millisecond conversion utility.
* <code>&nbsp;&nbsp;&nbsp;392</code> ![](https://img.shields.io/github/last-commit/gumroad/countdown.js) [countdown.js](https://github.com/gumroad/countdown.js) - Super simple countdowns.
* <code>&nbsp;&nbsp;4747</code> ![](https://img.shields.io/github/last-commit/hustcc/timeago.js) [timeago.js](https://github.com/hustcc/timeago.js) - Simple library (less then 2kb) used to format date with `*** time ago` statement.
* <code>&nbsp;&nbsp;1975</code> ![](https://img.shields.io/github/last-commit/taylorhakes/fecha) [fecha](https://github.com/taylorhakes/fecha) - Lightweight date formatting and parsing (~2KB). Meant to replace parsing and formatting functionality of moment.js.
* <code>&nbsp;28487</code> ![](https://img.shields.io/github/last-commit/date-fns/date-fns) [date-fns](https://github.com/date-fns/date-fns) - Modern JavaScript date utility library.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4</code> ![](https://img.shields.io/github/last-commit/dawidjaniga/map-countdown) [map-countdown](https://github.com/dawidjaniga/map-countdown) - A browser countdown built on top of the Google Maps.
* <code>&nbsp;38607</code> ![](https://img.shields.io/github/last-commit/iamkun/dayjs) [dayjs](https://github.com/iamkun/dayjs) - Day.js 2KB immutable date library alternative to Moment.js with the same modern API.
* <code>&nbsp;12356</code> ![](https://img.shields.io/github/last-commit/moment/luxon) [luxon](https://github.com/moment/luxon) - Luxon is a library for working with dates and times in JavaScript.

## String
*String Libraries.*

* <code>&nbsp;&nbsp;3437</code> ![](https://img.shields.io/github/last-commit/panzerdp/voca) [voca](https://github.com/panzerdp/voca) - The ultimate JavaScript string library
* <code>&nbsp;&nbsp;&nbsp;&nbsp;83</code> ![](https://img.shields.io/github/last-commit/EvandroLG/selecting) [selecting](https://github.com/EvandroLG/selecting) - A library that allows you to access the text selected by the user.
* <code>&nbsp;&nbsp;3359</code> ![](https://img.shields.io/github/last-commit/epeli/underscore.string) [underscore.string](https://github.com/epeli/underscore.string) - String manipulation extensions for Underscore.js JavaScript library.
* <code>&nbsp;&nbsp;1759</code> ![](https://img.shields.io/github/last-commit/jprichardson/string.js) [string.js](https://github.com/jprichardson/string.js) - Extra JavaScript string methods.
* <code>&nbsp;&nbsp;3032</code> ![](https://img.shields.io/github/last-commit/mathiasbynens/he) [he](https://github.com/mathiasbynens/he) - A robust HTML entity encoder/decoder written in JavaScript.
* <code>&nbsp;&nbsp;1428</code> ![](https://img.shields.io/github/last-commit/sindresorhus/multiline) [multiline](https://github.com/sindresorhus/multiline) - Multiline strings in JavaScript.
* <code>&nbsp;&nbsp;5912</code> ![](https://img.shields.io/github/last-commit/sindresorhus/query-string) [query-string](https://github.com/sindresorhus/query-string) - Parse and stringify URL query strings.
* <code>&nbsp;&nbsp;6142</code> ![](https://img.shields.io/github/last-commit/medialize/URI.js) [URI.js](https://github.com/medialize/URI.js/) - JavaScript URL mutation library.
* <code>&nbsp;&nbsp;&nbsp;499</code> ![](https://img.shields.io/github/last-commit/Mikhus/domurl) [jsurl](https://github.com/Mikhus/domurl) - Lightweight URL manipulation with JavaScript.
* <code>&nbsp;&nbsp;1992</code> ![](https://img.shields.io/github/last-commit/alexei/sprintf.js) [sprintf.js](https://github.com/alexei/sprintf.js) - A sprintf implementation.
* <code>&nbsp;&nbsp;&nbsp;548</code> ![](https://img.shields.io/github/last-commit/snd/url-pattern) [url-pattern](https://github.com/snd/url-pattern) - Easier than regex string matching patterns for urls and other strings. Turn strings into data or data into strings.
* <code>&nbsp;&nbsp;&nbsp;144</code> ![](https://img.shields.io/github/last-commit/plexis-js/plexis) [plexis](https://github.com/plexis-js/plexis) - Lo-fi, powerful, community-driven string manipulation library.

## Number

* <code>&nbsp;&nbsp;9157</code> ![](https://img.shields.io/github/last-commit/adamwdraper/Numeral-js) [Numeral-js](https://github.com/adamwdraper/Numeral-js) - A JavaScript library for formatting and manipulating numbers.
* <code>&nbsp;&nbsp;5937</code> ![](https://img.shields.io/github/last-commit/chancejs/chancejs) [chance.js](https://github.com/chancejs/chancejs) - Random generator helper in JavaScript. Can generate numbers, strings etc.
* <code>&nbsp;&nbsp;7161</code> ![](https://img.shields.io/github/last-commit/HubSpot/odometer) [odometer](https://github.com/HubSpot/odometer) - Smoothly transitions numbers with ease.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;32</code> ![](https://img.shields.io/github/last-commit/josscrowcroft/accounting.js) [accounting.js](https://github.com/josscrowcroft/accounting.js) - A lightweight JavaScript library for number, money and currency formatting - fully localisable, zero dependencies.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/josscrowcroft/money.js) [money.js](https://github.com/josscrowcroft/money.js) - A tiny (1kb) JavaScript currency conversion library, for web & nodeJS.
* <code>&nbsp;&nbsp;&nbsp;376</code> ![](https://img.shields.io/github/last-commit/infusion/Fraction.js) [Fraction.js](https://github.com/infusion/Fraction.js) - A rational number library for JavaScript.
* <code>&nbsp;&nbsp;&nbsp;199</code> ![](https://img.shields.io/github/last-commit/infusion/Complex.js) [Complex.js](https://github.com/infusion/Complex.js) - A complex number library for JavaScript.
* <code>&nbsp;&nbsp;&nbsp;101</code> ![](https://img.shields.io/github/last-commit/infusion/Polynomial.js) [Polynomial.js](https://github.com/infusion/Polynomial.js) - A polynomials library for JavaScript.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/infusion/Quaternion.js) [Quaternion.js](https://github.com/infusion/Quaternion.js) - A quaternion library for JavaScript


## Storage

* <code>&nbsp;13724</code> ![](https://img.shields.io/github/last-commit/marcuswestin/store.js) [store.js](https://github.com/marcuswestin/store.js) - LocalStorage wrapper for all browsers without using cookies or flash. Uses localStorage, globalStorage, and userData behavior under the hood.
* <code>&nbsp;20325</code> ![](https://img.shields.io/github/last-commit/mozilla/localForage) [localForage](https://github.com/mozilla/localForage) - Offline storage, improved. Wraps IndexedDB, WebSQL, or localStorage using a simple but powerful API.
* <code>&nbsp;&nbsp;1540</code> ![](https://img.shields.io/github/last-commit/andris9/jStorage) [jStorage](https://github.com/andris9/jStorage) - jStorage is a simple key/value database to store data on browser side.
* <code>&nbsp;&nbsp;2106</code> ![](https://img.shields.io/github/last-commit/zendesk/cross-storage) [cross-storage](https://github.com/zendesk/cross-storage) - Cross domain local storage, with permissions.
* <code>&nbsp;&nbsp;3372</code> ![](https://img.shields.io/github/last-commit/addyosmani/basket.js) [basket.js](https://github.com/addyosmani/basket.js) - A script and resource loader for caching & loading scripts with localStorage.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/nodeca/bag.js) [bag.js](https://github.com/nodeca/bag.js) - A caching script and resource loader, similar to basket.js, but with additional k/v interface and localStorage / websql / indexedDB support.
* <code>&nbsp;&nbsp;1976</code> ![](https://img.shields.io/github/last-commit/Wisembly/basil.js) [basil.js](https://github.com/Wisembly/basil.js) - The missing JavaScript smart persistent layer.
* <code>&nbsp;&nbsp;8656</code> ![](https://img.shields.io/github/last-commit/carhartl/jquery-cookie) [jquery-cookie](https://github.com/carhartl/jquery-cookie) - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
* <code>&nbsp;19325</code> ![](https://img.shields.io/github/last-commit/js-cookie/js-cookie) [js-cookie](https://github.com/js-cookie/js-cookie) - A simple, lightweight JavaScript API for handling browser cookies.
* <code>&nbsp;&nbsp;1785</code> ![](https://img.shields.io/github/last-commit/ScottHamper/Cookies) [Cookies](https://github.com/ScottHamper/Cookies) - JavaScript Client-Side Cookie Manipulation Library.
* <code>&nbsp;&nbsp;&nbsp;785</code> ![](https://img.shields.io/github/last-commit/aaronpowell/db.js) [DB.js](https://github.com/aaronpowell/db.js/) - Promise based IndexDB Wrapper library.
* <code>&nbsp;&nbsp;2141</code> ![](https://img.shields.io/github/last-commit/brianleroux/lawnchair) [lawnchair.js](https://github.com/brianleroux/lawnchair/) - Simple client-side JSON storage.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;78</code> ![](https://img.shields.io/github/last-commit/kripken/sql.js) [sql.js](https://github.com/kripken/sql.js) - SQLite compiled to JavaScript through Emscripten.
* <code>&nbsp;14878</code> ![](https://img.shields.io/github/last-commit/pouchdb/pouchdb) [pouchdb](https://github.com/pouchdb/pouchdb) - Javascript db inspired by Apache CouchDB to run well within the browser.
* <code>&nbsp;&nbsp;&nbsp;234</code> ![](https://img.shields.io/github/last-commit/nirtz89/crumbsjs) [crumbsjs](https://github.com/nirtz89/crumbsjs) - A lightweight vanilla ES6 cookies and local storage JavaScript library.
* <code>&nbsp;&nbsp;&nbsp;396</code> ![](https://img.shields.io/github/last-commit/softvar/awesome-web-storage) [awesome-web-storage](https://github.com/softvar/awesome-web-storage) - Everything you need to know about client-side storage.
* <code>&nbsp;&nbsp;&nbsp;238</code> ![](https://img.shields.io/github/last-commit/StanfordHCI/datavore) [datavore](https://github.com/StanfordHCI/datavore) - A small, fast, in-browser database engine written in JavaScript.
* <code>&nbsp;&nbsp;4310</code> ![](https://img.shields.io/github/last-commit/hoodiehq/hoodie) [Hoodie](https://github.com/hoodiehq/hoodie) - Offline First backend to work in browser without internet connectivity.
* <code>&nbsp;13028</code> ![](https://img.shields.io/github/last-commit/louischatriot/nedb) [NeDB](https://github.com/louischatriot/nedb) - Embedded Persistent database for Browsers, nw.js, electron.

## Color

* <code>&nbsp;&nbsp;5800</code> ![](https://img.shields.io/github/last-commit/davidmerfield/randomColor) [randomColor](https://github.com/davidmerfield/randomColor) - A color generator for JavaScript.
* <code>&nbsp;&nbsp;8773</code> ![](https://img.shields.io/github/last-commit/gka/chroma.js) [chroma.js](https://github.com/gka/chroma.js) - JavaScript library for all kinds of color manipulations.
* <code>&nbsp;&nbsp;4261</code> ![](https://img.shields.io/github/last-commit/Qix-/color) [color](https://github.com/Qix-/color) - JavaScript color conversion and manipulation library.
* <code>&nbsp;&nbsp;9100</code> ![](https://img.shields.io/github/last-commit/mrmrs/colors) [colors](https://github.com/mrmrs/colors) - Smarter defaults for colors on the web.
* <code>&nbsp;&nbsp;2270</code> ![](https://img.shields.io/github/last-commit/Fooidge/PleaseJS) [PleaseJS](https://github.com/Fooidge/PleaseJS) - JavaScript Library for creating random pleasing colors and color schemes.
* <code>&nbsp;&nbsp;4233</code> ![](https://img.shields.io/github/last-commit/bgrins/TinyColor) [TinyColor](https://github.com/bgrins/TinyColor) - Fast, small color manipulation and conversion for JavaScript.
* <code>&nbsp;&nbsp;4598</code> ![](https://img.shields.io/github/last-commit/jariz/vibrant.js) [Vibrant.js](https://github.com/jariz/vibrant.js/) - Extract prominent colors from an image.

## I18n And L10n
*Localization (l10n) and internationalization (i18n) JavaScript libraries.*

* <code>&nbsp;&nbsp;6163</code> ![](https://img.shields.io/github/last-commit/i18next/i18next) [i18next](https://github.com/i18next/i18next) - internationalisation (i18n) with JavaScript the easy way.
* <code>&nbsp;&nbsp;3516</code> ![](https://img.shields.io/github/last-commit/airbnb/polyglot.js) [polyglot](https://github.com/airbnb/polyglot.js) - tiny i18n helper library.
* <code>&nbsp;&nbsp;&nbsp;238</code> ![](https://img.shields.io/github/last-commit/nodeca/babelfish) [babelfish](https://github.com/nodeca/babelfish/) - i18n with human friendly API and built in plurals support.
* <code>&nbsp;&nbsp;&nbsp;293</code> ![](https://img.shields.io/github/last-commit/ttag-org/ttag) [ttag](https://github.com/ttag-org/ttag) - Modern javascript i18n localization library based on ES6 tagged templates and the good old GNU gettext.

## Control Flow

* <code>&nbsp;27515</code> ![](https://img.shields.io/github/last-commit/caolan/async) [async](https://github.com/caolan/async) - Async utilities for node and the browser.
* <code>&nbsp;14963</code> ![](https://img.shields.io/github/last-commit/kriskowal/q) [q](https://github.com/kriskowal/q) - A tool for making and composing asynchronous promises in JavaScript.
* <code>&nbsp;&nbsp;2223</code> ![](https://img.shields.io/github/last-commit/creationix/step) [step](https://github.com/creationix/step/) - An async control-flow library that makes stepping through logic easy.
* <code>&nbsp;&nbsp;&nbsp;766</code> ![](https://img.shields.io/github/last-commit/bevacqua/contra) [contra](https://github.com/bevacqua/contra/) - Asynchronous flow control with a functional taste to it.
* <code>&nbsp;20019</code> ![](https://img.shields.io/github/last-commit/petkaantonov/bluebird) [Bluebird](https://github.com/petkaantonov/bluebird/) - fully featured promise library with focus on innovative features and performance.
* <code>&nbsp;&nbsp;3439</code> ![](https://img.shields.io/github/last-commit/cujojs/when) [when](https://github.com/cujojs/when) - A solid, fast Promises/A+ and when() implementation, plus other async goodies.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;10</code> ![](https://img.shields.io/github/last-commit/gartz/ObjectEventTarget) [ObjectEventTarget](https://github.com/gartz/ObjectEventTarget) - Provide a prototype that add support to event listeners (with same behavior of EventTarget from DOMElements available on browsers).
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/marcoonroad/sporadic) [sporadic](https://github.com/marcoonroad/sporadic) - Composable concurrency abstractions (such as streams, coroutines and Go-like channels) on top of promises, for Node and browser engines.


## Routing

* <code>&nbsp;&nbsp;5604</code> ![](https://img.shields.io/github/last-commit/flatiron/director) [director](https://github.com/flatiron/director) - A tiny and isomorphic URL router for JavaScript.
* <code>&nbsp;&nbsp;7483</code> ![](https://img.shields.io/github/last-commit/visionmedia/page.js) [page.js](https://github.com/visionmedia/page.js) - Micro client-side router inspired by the Express router (~1200 bytes).
* <code>&nbsp;&nbsp;1088</code> ![](https://img.shields.io/github/last-commit/mtrpcic/pathjs) [pathjs](https://github.com/mtrpcic/pathjs) - Simple, lightweight routing for web browsers.
* <code>&nbsp;&nbsp;1442</code> ![](https://img.shields.io/github/last-commit/millermedeiros/crossroads.js) [crossroads](https://github.com/millermedeiros/crossroads.js) - JavaScript Routes.
* <code>&nbsp;&nbsp;&nbsp;531</code> ![](https://img.shields.io/github/last-commit/olivernn/davis.js) [davis.js](https://github.com/olivernn/davis.js) - RESTful degradable JavaScript routing using pushState.
* <code>&nbsp;&nbsp;&nbsp;713</code> ![](https://img.shields.io/github/last-commit/lukeed/navaid) [navaid](https://github.com/lukeed/navaid) - A navigation aid (aka, router) for the browser in 850 bytes~!


## Security

* <code>&nbsp;&nbsp;8792</code> ![](https://img.shields.io/github/last-commit/cure53/DOMPurify) [DOMPurify](https://github.com/cure53/DOMPurify) - A DOM-only, super-fast, uber-tolerant XSS sanitizer for HTML, MathML and SVG.
* <code>&nbsp;&nbsp;4498</code> ![](https://img.shields.io/github/last-commit/leizongmin/js-xss) [js-xss](https://github.com/leizongmin/js-xss) - Sanitize untrusted HTML (to prevent XSS) with a configuration specified by a Whitelist.
* <code>&nbsp;&nbsp;1053</code> ![](https://img.shields.io/github/last-commit/yahoo/xss-filters) [xss-filters](https://github.com/yahoo/xss-filters) - Secure XSS Filters by Yahoo.
* <code>&nbsp;&nbsp;2944</code> ![](https://img.shields.io/github/last-commit/apostrophecms/sanitize-html) [sanitize-html](https://github.com/apostrophecms/sanitize-html) - sanitize-html provides a simple HTML sanitizer with a clear API.


## Log

* <code>&nbsp;&nbsp;2879</code> ![](https://img.shields.io/github/last-commit/adamschwartz/log) [log](https://github.com/adamschwartz/log) - Console.log with style.
* <code>&nbsp;&nbsp;&nbsp;205</code> ![](https://img.shields.io/github/last-commit/Oaxoa/Conzole) [Conzole](https://github.com/Oaxoa/Conzole) - A debug panel built in JavaScript that wraps JavaScript native console object methods and functionality in a panel displayed inside the page.
* <code>&nbsp;&nbsp;&nbsp;407</code> ![](https://img.shields.io/github/last-commit/patik/console.log-wrapper) [console.log-wrapper](https://github.com/patik/console.log-wrapper) - Log to the console in any browser with clarity.
* <code>&nbsp;&nbsp;2217</code> ![](https://img.shields.io/github/last-commit/pimterry/loglevel) [loglevel](https://github.com/pimterry/loglevel) - Minimal lightweight logging for JavaScript, adding reliable log level methods to wrap any available console.log methods.
* [minilog](http://mixu.net/minilog/) – Lightweight client & server-side logging with Stream-API backends.
* [storyboard](http://guigrpa.github.io/storyboard/) - Universal logging library + Chrome extension; it lets you see all client and server tasks triggered by a user action in a single place.

## RegExp
* [RegEx101](https://regex101.com/#javascript) - Online regex tester and debugger for JavaScript. Also supports Python, PHP and PCRE.
* [RegExr](https://regexr.com/) - HTML/JS based tool for creating, testing, and learning about Regular Expressions.


## Voice Command

* <code>&nbsp;&nbsp;6269</code> ![](https://img.shields.io/github/last-commit/TalAter/annyang) [annyang](https://github.com/TalAter/annyang) - A JavaScript library for adding voice commands to your site, using speech recognition.
* <code>&nbsp;&nbsp;&nbsp;544</code> ![](https://img.shields.io/github/last-commit/pazguille/voix) [voix.js](https://github.com/pazguille/voix) - A JavaScript library to add voice commands to your sites, apps or games.


## API

* <code>&nbsp;92557</code> ![](https://img.shields.io/github/last-commit/axios/axios) [axios](https://github.com/axios/axios) - Promise based HTTP client for the browser and node.js.
* <code>&nbsp;&nbsp;1300</code> ![](https://img.shields.io/github/last-commit/SGrondin/bottleneck) [bottleneck](https://github.com/SGrondin/bottleneck) - A powerful rate limiter that makes throttling easy.
* <code>&nbsp;&nbsp;&nbsp;226</code> ![](https://img.shields.io/github/last-commit/bettiolo/oauth-signature-js) [oauth-signature-js](https://github.com/bettiolo/oauth-signature-js) - JavaScript OAuth 1.0a signature generator for node and the browser.
* <code>&nbsp;&nbsp;&nbsp;392</code> ![](https://img.shields.io/github/last-commit/lincolnloop/amygdala) [amygdala](https://github.com/lincolnloop/amygdala) - RESTful HTTP client for JavaScript powered web applications.
* <code>&nbsp;&nbsp;&nbsp;616</code> ![](https://img.shields.io/github/last-commit/jpillora/jquery.rest) [jquery.rest](https://github.com/jpillora/jquery.rest) - A jQuery plugin for easy consumption of RESTful APIs.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;36</code> ![](https://img.shields.io/github/last-commit/victor-am/rails-ranger) [Rails Ranger](https://github.com/victor-am/rails-ranger) - An opinionated REST client for Ruby on Rails APIs.
* <code>&nbsp;&nbsp;2366</code> ![](https://img.shields.io/github/last-commit/elbywan/wretch) [wretch](https://github.com/elbywan/wretch) - A tiny wrapper built around fetch with an intuitive syntax.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;20</code> ![](https://img.shields.io/github/last-commit/Bearer/bearer-js) [Bearer.sh](https://github.com/Bearer/bearer-js) - Universal API client that supports OAuth / API Key / Basic / etc.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;51</code> ![](https://img.shields.io/github/last-commit/WebsiteBeaver/far-fetch) [FarFetch](https://github.com/WebsiteBeaver/far-fetch) - Modern Fetch API wrapper for simplicity, with concise file uploading.
* <code>&nbsp;&nbsp;&nbsp;968</code> ![](https://img.shields.io/github/last-commit/opticdev/optic) [Optic](https://github.com/opticdev/optic) - Optic automatically documents and tests your APIs.
* <code>&nbsp;21938</code> ![](https://img.shields.io/github/last-commit/vercel/swr) [SWR](https://github.com/vercel/swr) - React Hooks library for remote data fetching.
* <code>&nbsp;26807</code> ![](https://img.shields.io/github/last-commit/tannerlinsley/react-query) [React Query](https://github.com/tannerlinsley/react-query) - Hooks for fetching, caching and updating asynchronous data in React.

## Streaming

* <code>&nbsp;&nbsp;1677</code> ![](https://img.shields.io/github/last-commit/zalando/tailor) [Tailor](https://github.com/zalando/tailor) - Streaming layout service for front-end microservices, inspired by Facebook's BigPipe.


## Vision Detection

* <code>&nbsp;&nbsp;9105</code> ![](https://img.shields.io/github/last-commit/eduardolundgren/tracking.js) [tracking.js](https://github.com/eduardolundgren/tracking.js) - A modern approach for Computer Vision on the web.
* <code>&nbsp;&nbsp;3365</code> ![](https://img.shields.io/github/last-commit/antimatter15/ocrad.js) [ocrad.js](https://github.com/antimatter15/ocrad.js) - OCR in JavaScript via Emscripten.


## Machine Learning

* <code>&nbsp;10318</code> ![](https://img.shields.io/github/last-commit/karpathy/convnetjs) [ConvNetJS](https://github.com/karpathy/convnetjs) - Deep Learning in JavaScript. Train Convolutional Neural Networks (or ordinary ones) in your browser.
* <code>&nbsp;&nbsp;&nbsp;463</code> ![](https://img.shields.io/github/last-commit/dn2a/dn2a-javascript) [DN2A](https://github.com/dn2a/dn2a-javascript) - Digital Neural Networks Architecture.
* <code>&nbsp;&nbsp;8016</code> ![](https://img.shields.io/github/last-commit/harthur/brain) [Brain.js](https://github.com/harthur/brain) - Neural networks in JavaScript.
* <code>&nbsp;&nbsp;1474</code> ![](https://img.shields.io/github/last-commit/stevenmiller888/mind) [Mind.js](https://github.com/stevenmiller888/mind) - A flexible neural network library.
* <code>&nbsp;&nbsp;6817</code> ![](https://img.shields.io/github/last-commit/cazala/synaptic) [Synaptic.js](https://github.com/cazala/synaptic) - Architecture-free neural network library for node.js and the browser.
* [TensorFlow.js](https://www.tensorflow.org/js/) - A JavaScript library for training and deploying ML models in the browser and on Node.js.
* [ml5.js](https://ml5js.org) - Friendly Machine Learning for the Web.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;63</code> ![](https://img.shields.io/github/last-commit/mrdimosthenis/Synapses) [Synapses](https://github.com/mrdimosthenis/Synapses) - Lightweight cross-platform Neural Network library.
* <code>&nbsp;&nbsp;2077</code> ![](https://img.shields.io/github/last-commit/BayesWitnesses/m2cgen) [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native JavaScript code with zero dependencies.


## Browser Detection

* <code>&nbsp;&nbsp;5078</code> ![](https://img.shields.io/github/last-commit/ded/bowser) [bowser](https://github.com/ded/bowser) - a browser detector.

## Operating System
* <code>&nbsp;&nbsp;5975</code> ![](https://img.shields.io/github/last-commit/os-js/OS.js) [os.js](https://github.com/os-js/OS.js) - An open-source web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more.

## Benchmark

* <code>&nbsp;&nbsp;5129</code> ![](https://img.shields.io/github/last-commit/bestiejs/benchmark.js) [benchmark.js](https://github.com/bestiejs/benchmark.js) - A benchmarking library. As used on jsPerf.com.
* <code>&nbsp;&nbsp;&nbsp;551</code> ![](https://img.shields.io/github/last-commit/logicalparadox/matcha) [matcha](https://github.com/logicalparadox/matcha) - A caffeine driven, simplistic approach to benchmarking.

## Code highlighting

* <code>&nbsp;19832</code> ![](https://img.shields.io/github/last-commit/isagalaev/highlight.js) [Highlight.js](https://github.com/isagalaev/highlight.js) - JavaScript syntax highlighter.
* <code>&nbsp;10164</code> ![](https://img.shields.io/github/last-commit/PrismJS/prism) [PrismJS](https://github.com/PrismJS/prism) - Lightweight, robust, elegant syntax highlighting.


## Loading Status
*Libraries for indicate load status.*

* <code>&nbsp;&nbsp;1549</code> ![](https://img.shields.io/github/last-commit/lightningtgc/MProgress.js) [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - Create Google Material Design progress linear bars.
* [NProgress](https://ricostacruz.com/nprogress/) - Slim progress bars for Ajax'y applications.
* <code>&nbsp;&nbsp;9336</code> ![](https://img.shields.io/github/last-commit/fgnass/spin.js) [Spin.js](https://github.com/fgnass/spin.js) - A spinning activity indicator.
* <code>&nbsp;&nbsp;2371</code> ![](https://img.shields.io/github/last-commit/usablica/progress.js) [progress.js](https://github.com/usablica/progress.js) - Create and manage progress bar for every objects on the page.
* <code>&nbsp;&nbsp;7549</code> ![](https://img.shields.io/github/last-commit/kimmobrunfeldt/progressbar.js) [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - Beautiful and responsive progress bars with animated SVG paths.
* <code>&nbsp;15417</code> ![](https://img.shields.io/github/last-commit/HubSpot/pace) [pace](https://github.com/HubSpot/pace) - Automatically add a progress bar to your site.
* <code>&nbsp;&nbsp;&nbsp;338</code> ![](https://img.shields.io/github/last-commit/buunguyen/topbar) [topbar](https://github.com/buunguyen/topbar) - Tiny & beautiful site-wide progress indicator.
* <code>&nbsp;&nbsp;2843</code> ![](https://img.shields.io/github/last-commit/jacoborus/nanobar) [nanobar](https://github.com/jacoborus/nanobar) - Very lightweight progress bars. No jQuery.
* <code>&nbsp;&nbsp;&nbsp;624</code> ![](https://img.shields.io/github/last-commit/codrops/PageLoadingEffects) [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - Modern ways of revealing new content using SVG animations.
* <code>&nbsp;18774</code> ![](https://img.shields.io/github/last-commit/tobiasahlin/SpinKit) [SpinKit](https://github.com/tobiasahlin/SpinKit) - A collection of loading indicators animated with CSS.
* <code>&nbsp;&nbsp;7852</code> ![](https://img.shields.io/github/last-commit/hakimel/Ladda) [Ladda](https://github.com/hakimel/Ladda) - Buttons with built-in loading indicators.
* <code>&nbsp;&nbsp;6866</code> ![](https://img.shields.io/github/last-commit/lukehaas/css-loaders) [css-loaders](https://github.com/lukehaas/css-loaders) - A collection of loading spinners animated with CSS


## Validation

* <code>&nbsp;&nbsp;9033</code> ![](https://img.shields.io/github/last-commit/guillaumepotier/Parsley.js) [Parsley.js](https://github.com/guillaumepotier/Parsley.js) - Validate your forms, frontend, without writing a single line of JavaScript.
* <code>&nbsp;10170</code> ![](https://img.shields.io/github/last-commit/jzaefferer/jquery-validation) [jquery-validation](https://github.com/jzaefferer/jquery-validation) - jQuery Validation Plugin.
* <code>&nbsp;19426</code> ![](https://img.shields.io/github/last-commit/chriso/validator.js) [validator.js](https://github.com/chriso/validator.js) - String validation and sanitization.
* <code>&nbsp;&nbsp;2543</code> ![](https://img.shields.io/github/last-commit/rickharrison/validate.js) [validate.js](https://github.com/rickharrison/validate.js) - Lightweight JavaScript form validation library inspired by CodeIgniter.
* <code>&nbsp;&nbsp;&nbsp;279</code> ![](https://img.shields.io/github/last-commit/jaymorrow/validatr) [validatr](https://github.com/jaymorrow/validatr/) - Cross Browser HTML5 Form Validation.
* [FormValidation](https://formvalidation.io/) - The best jQuery plugin to validate form fields. Formerly BootstrapValidator.
* <code>&nbsp;&nbsp;9164</code> ![](https://img.shields.io/github/last-commit/arasatasaygin/is.js) [is.js](https://github.com/arasatasaygin/is.js) - Check types, regexps, presence, time and more.
* <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/FieldVal/fieldval-js) [FieldVal](https://github.com/FieldVal/fieldval-js) - multipurpose validation library. Supports both sync and async validation.
* <code>&nbsp;&nbsp;&nbsp;292</code> ![](https://img.shields.io/github/last-commit/neuledge/funval) [Funval](https://github.com/neuledge/funval) - Data validation using functions interfaces (support TypeScript).
* <code>&nbsp;&nbsp;1822</code> ![](https://img.shields.io/github/last-commit/ealush/vest) [vest](https://github.com/ealush/vest) - 🦺 Declarative form validation framework inspired by unit testing.


## Keyboard Wrappers

* <code>&nbsp;11050</code> ![](https://img.shields.io/github/last-commit/ccampbell/mousetrap) [mousetrap](https://github.com/ccampbell/mousetrap) - Simple library for handling keyboard shortcuts in JavaScript.
* <code>&nbsp;&nbsp;6479</code> ![](https://img.shields.io/github/last-commit/madrobby/keymaster) [keymaster](https://github.com/madrobby/keymaster) - A simple micro-library for defining and dispatching keyboard shortcuts.
* <code>&nbsp;&nbsp;3201</code> ![](https://img.shields.io/github/last-commit/dmauro/Keypress) [Keypress](https://github.com/dmauro/Keypress) - A keyboard input capturing utility in which any key can be a modifier key.
* <code>&nbsp;&nbsp;1934</code> ![](https://img.shields.io/github/last-commit/RobertWHurst/KeyboardJS) [KeyboardJS](https://github.com/RobertWHurst/KeyboardJS) - A JavaScript library for binding keyboard combos without the pain of key codes and key combo conflicts.
* <code>&nbsp;&nbsp;2577</code> ![](https://img.shields.io/github/last-commit/jeresig/jquery.hotkeys) [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys) - jQuery Hotkeys lets you watch for keyboard events anywhere in your code supporting almost any key combination.
* <code>&nbsp;&nbsp;1218</code> ![](https://img.shields.io/github/last-commit/keithamus/jwerty) [jwerty](https://github.com/keithamus/jwerty) - Awesome handling of keyboard events.


## Tours And Guides

* <code>&nbsp;21133</code> ![](https://img.shields.io/github/last-commit/usablica/intro.js) [intro.js](https://github.com/usablica/intro.js) - A better way for new feature introduction and step-by-step users guide for your website and project.
* <code>&nbsp;10148</code> ![](https://img.shields.io/github/last-commit/HubSpot/shepherd) [shepherd](https://github.com/HubSpot/shepherd) - Guide your users through a tour of your app.
* <code>&nbsp;&nbsp;4413</code> ![](https://img.shields.io/github/last-commit/sorich87/bootstrap-tour) [bootstrap-tour](https://github.com/sorich87/bootstrap-tour) - Quick and easy product tours with Twitter Bootstrap Popovers.
* <code>&nbsp;&nbsp;1234</code> ![](https://img.shields.io/github/last-commit/easelinc/tourist) [tourist](https://github.com/easelinc/tourist) - Simple, flexible tours for your app.
* <code>&nbsp;&nbsp;5011</code> ![](https://img.shields.io/github/last-commit/heelhook/chardin.js) [chardin.js](https://github.com/heelhook/chardin.js) - Simple overlay instructions for your apps.
* <code>&nbsp;&nbsp;&nbsp;905</code> ![](https://img.shields.io/github/last-commit/tracelytics/pageguide) [pageguide](https://github.com/tracelytics/pageguide) - An interactive guide for web page elements using jQuery and CSS3.
* <code>&nbsp;&nbsp;4248</code> ![](https://img.shields.io/github/last-commit/linkedin/hopscotch) [hopscotch](https://github.com/linkedin/hopscotch) - A framework to make it easy for developers to add product tours to their pages.
* <code>&nbsp;&nbsp;1433</code> ![](https://img.shields.io/github/last-commit/zurb/joyride) [joyride](https://github.com/zurb/joyride) - jQuery feature tour plugin.
* <code>&nbsp;&nbsp;1076</code> ![](https://img.shields.io/github/last-commit/zzarcon/focusable) [focusable](https://github.com/zzarcon/focusable) - Set a spotlight focus on DOM element adding a overlay layer to the rest of the page.
* <code>&nbsp;13472</code> ![](https://img.shields.io/github/last-commit/kamranahmedse/driver.js) [driver.js](https://github.com/kamranahmedse/driver.js) - Powerful yet light-weight, vanilla JavaScript engine to drive the user's focus across the page

## Notifications

* <code>&nbsp;&nbsp;2366</code> ![](https://img.shields.io/github/last-commit/dolce/iziToast) [iziToast](https://github.com/dolce/iziToast) - Elegant, responsive, flexible and lightweight notification plugin with no dependencies.
* <code>&nbsp;&nbsp;4053</code> ![](https://img.shields.io/github/last-commit/HubSpot/messenger) [messenger](https://github.com/HubSpot/messenger) - Growl-style alerts and messages for your app.
* <code>&nbsp;&nbsp;6716</code> ![](https://img.shields.io/github/last-commit/needim/noty) [noty](https://github.com/needim/noty) - jQuery notification plugin.
* <code>&nbsp;&nbsp;3617</code> ![](https://img.shields.io/github/last-commit/sciactive/pnotify) [pnotify](https://github.com/sciactive/pnotify) - JavaScript notifications for Bootstrap, jQuery UI, and the Web Notifications Draft.
* <code>&nbsp;11193</code> ![](https://img.shields.io/github/last-commit/CodeSeven/toastr) [toastr](https://github.com/CodeSeven/toastr) - Simple JavaScript toast notifications.
* <code>&nbsp;&nbsp;2083</code> ![](https://img.shields.io/github/last-commit/wavded/humane-js) [humane-js](https://github.com/wavded/humane-js) - A simple, modern, browser notification system.
* <code>&nbsp;&nbsp;&nbsp;936</code> ![](https://img.shields.io/github/last-commit/hxgf/smoke.js) [smoke.js](https://github.com/hxgf/smoke.js) - Framework-agnostic styled alert system for JavaScript.
* <code>&nbsp;&nbsp;6196</code> ![](https://img.shields.io/github/last-commit/jaredreich/notie) [notie](https://github.com/jaredreich/notie) - Simple notifications and inputs with no dependencies.
* <code>&nbsp;&nbsp;3407</code> ![](https://img.shields.io/github/last-commit/notifirehq/notifire) [notifire](https://github.com/notifirehq/notifire) - Open-source notification infrastructure for products.


## Sliders

* <code>&nbsp;30759</code> ![](https://img.shields.io/github/last-commit/nolimits4web/Swiper) [Swiper](https://github.com/nolimits4web/Swiper) - Mobile touch slider and framework with hardware accelerated transitions.
* <code>&nbsp;27426</code> ![](https://img.shields.io/github/last-commit/kenwheeler/slick) [slick](https://github.com/kenwheeler/slick) - The last carousel you'll ever need.
* [slidesJs](http://www.slidesjs.com) - Is a responsive slideshow plug-in for JQuery(1.7.1+) with features like touch and CSS3 transitions
* <code>&nbsp;&nbsp;4945</code> ![](https://img.shields.io/github/last-commit/woothemes/FlexSlider) [FlexSlider](https://github.com/woothemes/FlexSlider) - An awesome, fully responsive jQuery slider plugin.
* <code>&nbsp;&nbsp;2897</code> ![](https://img.shields.io/github/last-commit/darsain/sly) [sly](https://github.com/darsain/sly) - JavaScript library for one-directional scrolling with item based navigation support.
* <code>&nbsp;&nbsp;1796</code> ![](https://img.shields.io/github/last-commit/jaysalvat/vegas) [vegas](https://github.com/jaysalvat/vegas) - A jQuery plugin to add beautiful fullscreen backgrounds to your webpages. It even allows Slideshows.
* <code>&nbsp;&nbsp;3382</code> ![](https://img.shields.io/github/last-commit/IanLunn/Sequence) [Sequence](https://github.com/IanLunn/Sequence) - CSS animation framework for creating responsive sliders, presentations, banners, and other step-based applications.
* <code>&nbsp;59406</code> ![](https://img.shields.io/github/last-commit/hakimel/reveal.js) [reveal.js](https://github.com/hakimel/reveal.js) - A framework for easily creating beautiful presentations using HTML.
* <code>&nbsp;36643</code> ![](https://img.shields.io/github/last-commit/impress/impress.js) [impress.js](https://github.com/impress/impress.js) - It's a presentation framework based on the power of CSS3 transforms and transitions in modern browsers and inspired by the idea behind prezi.com.
* <code>&nbsp;&nbsp;4631</code> ![](https://img.shields.io/github/last-commit/bespokejs/bespoke) [bespoke.js](https://github.com/bespokejs/bespoke) - DIY Presentation Micro-Framework
* <code>&nbsp;&nbsp;1614</code> ![](https://img.shields.io/github/last-commit/tantaman/Strut) [Strut](https://github.com/tantaman/Strut) - Strut - An Impress.js and Bespoke.js Presentation Editor
* <code>&nbsp;21740</code> ![](https://img.shields.io/github/last-commit/dimsemenov/PhotoSwipe) [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe) - JavaScript image gallery for mobile and desktop, modular, framework independent.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;54</code> ![](https://img.shields.io/github/last-commit/JoanClaret/jcSlider) [jcSlider](https://github.com/JoanClaret/jcSlider) - A responsive slider jQuery plugin with CSS animations.
* <code>&nbsp;&nbsp;&nbsp;547</code> ![](https://img.shields.io/github/last-commit/jcobb/basic-jquery-slider) [basic-jquery-slider](https://github.com/jcobb/basic-jquery-slider) - Simple to use, simple to theme, simple to customise.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;53</code> ![](https://img.shields.io/github/last-commit/creative-punch/jQuery.adaptive-slider) [jQuery.adaptive-slider](https://github.com/creative-punch/jQuery.adaptive-slider/) - A jQuery plugin for a slider with adaptive colored figcaption and navigation.
* <code>&nbsp;&nbsp;1559</code> ![](https://img.shields.io/github/last-commit/bchanx/slidr) [slidr](https://github.com/bchanx/slidr) - add some slide effects.
* <code>&nbsp;&nbsp;7037</code> ![](https://img.shields.io/github/last-commit/metafizzy/flickity) [Flickity](https://github.com/metafizzy/flickity) - Touch, responsive, flickable galleries.
* <code>&nbsp;&nbsp;6398</code> ![](https://img.shields.io/github/last-commit/jedrzejchalubek/glidejs) [Glide.js](https://github.com/jedrzejchalubek/glidejs) - Responsive and touch-friendly jQuery slider. It's simple, lightweight and fast.
* <code>&nbsp;&nbsp;2129</code> ![](https://img.shields.io/github/last-commit/davidcetinkaya/embla-carousel) [Embla Carousel](https://github.com/davidcetinkaya/embla-carousel) - An extensible low level carousel for the web, written in TypeScript.

## Range Sliders

* <code>&nbsp;&nbsp;2512</code> ![](https://img.shields.io/github/last-commit/IonDen/ion.rangeSlider) [Ion.RangeSlider](https://github.com/IonDen/ion.rangeSlider) - Powerful and easily customizable range slider with many options and skin support.
* <code>&nbsp;&nbsp;&nbsp;676</code> ![](https://img.shields.io/github/last-commit/ghusse/jQRangeSlider) [jQRangeSlider](https://github.com/ghusse/jQRangeSlider) - A JavaScript slider selector that supports dates.
* <code>&nbsp;&nbsp;5213</code> ![](https://img.shields.io/github/last-commit/leongersen/noUiSlider) [noUiSlider](https://github.com/leongersen/noUiSlider) - A lightweight, highly customizable range slider without bloat.
* <code>&nbsp;&nbsp;2150</code> ![](https://img.shields.io/github/last-commit/andreruffert/rangeslider.js) [rangeslider.js](https://github.com/andreruffert/rangeslider.js) - HTML5 input range slider element polyfill.


## Form Widgets

### Input

* <code>&nbsp;16391</code> ![](https://img.shields.io/github/last-commit/twitter/typeahead.js) [typeahead.js](https://github.com/twitter/typeahead.js) - A fast and fully-featured autocomplete library.
* <code>&nbsp;&nbsp;2498</code> ![](https://img.shields.io/github/last-commit/aehlke/tag-it) [tag-it](https://github.com/aehlke/tag-it) - A jQuery UI plugin to handle multi-tag fields as well as tag suggestions/autocomplete.
* <code>&nbsp;&nbsp;5292</code> ![](https://img.shields.io/github/last-commit/ichord/At.js) [At.js](https://github.com/ichord/At.js) - Add GitHub like mentions autocomplete to your application.
* <code>&nbsp;&nbsp;&nbsp;959</code> ![](https://img.shields.io/github/last-commit/jamesallardice/Placeholders.js) [Placeholders.js](https://github.com/jamesallardice/Placeholders.js) - A JavaScript polyfill for the HTML5 placeholder attribute.
* <code>&nbsp;&nbsp;1940</code> ![](https://img.shields.io/github/last-commit/yairEO/fancyInput) [fancyInput](https://github.com/yairEO/fancyInput) - Makes typing in input fields fun with CSS3 effects.
* <code>&nbsp;&nbsp;2308</code> ![](https://img.shields.io/github/last-commit/xoxco/jQuery-Tags-Input) [jQuery-Tags-Input](https://github.com/xoxco/jQuery-Tags-Input) - Magically convert a simple text input into a cool tag list with this jQuery plugin.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5</code> ![](https://img.shields.io/github/last-commit/BankFacil/vanilla-masker) [vanilla-masker](https://github.com/BankFacil/vanilla-masker) - A pure JavaScript mask input.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;69</code> ![](https://img.shields.io/github/last-commit/IonDen/ion.checkRadio) [Ion.CheckRadio](https://github.com/IonDen/ion.checkRadio) - jQuery plugin for styling checkboxes and radio-buttons. With skin support.
* <code>&nbsp;&nbsp;6848</code> ![](https://img.shields.io/github/last-commit/LeaVerou/awesomplete) [awesomplete](https://github.com/LeaVerou/awesomplete) - Ultra lightweight, usable, beautiful autocomplete with zero dependencies. - https://projects.verou.me/awesomplete/

### Calendar

* <code>&nbsp;&nbsp;7748</code> ![](https://img.shields.io/github/last-commit/amsul/pickadate.js) [pickadate.js](https://github.com/amsul/pickadate.js) - The mobile-friendly, responsive, and lightweight jQuery date & time input picker.
* <code>&nbsp;12496</code> ![](https://img.shields.io/github/last-commit/eternicode/bootstrap-datepicker) [bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap forked from Stefan Petre's (of eyecon.ro), improvements by @eternicode.
* <code>&nbsp;&nbsp;7808</code> ![](https://img.shields.io/github/last-commit/dbushell/Pikaday) [Pikaday](https://github.com/dbushell/Pikaday) - A refreshing JavaScript Datepicker — lightweight, no dependencies, modular CSS.
* <code>&nbsp;14894</code> ![](https://img.shields.io/github/last-commit/fullcalendar/fullcalendar) [fullcalendar](https://github.com/fullcalendar/fullcalendar) - Full-sized drag & drop event calendar (jQuery plugin).
* <code>&nbsp;&nbsp;2908</code> ![](https://img.shields.io/github/last-commit/bevacqua/rome) [rome](https://github.com/bevacqua/rome) - A customizable date (and time) picker. Dependency free, opt-in UI.
* <code>&nbsp;10336</code> ![](https://img.shields.io/github/last-commit/dangrossman/daterangepicker) [Date Range Picker](https://github.com/dangrossman/daterangepicker) - creates a dropdown menu from which a user can select a range of dates.
* <code>&nbsp;&nbsp;1541</code> ![](https://img.shields.io/github/last-commit/duetds/date-picker) [Duet Date Picker](https://github.com/duetds/date-picker) - open source version of Duet Design System’s accessible date picker, WCAG 2.1 accessibility complaint
* <code>&nbsp;&nbsp;9820</code> ![](https://img.shields.io/github/last-commit/nhn/tui.calendar) [tui.calendar](https://github.com/nhn/tui.calendar) - A JavaScript schedule calendar that is full featured. Now your service just got the customizable calendar.

### Select

* <code>&nbsp;12795</code> ![](https://img.shields.io/github/last-commit/selectize/selectize.js) [selectize.js](https://github.com/selectize/selectize.js) - Selectize is the hybrid of a textbox and `<select>` box. It's jQuery based and it has autocomplete and native-feeling keyboard navigation; useful for tagging, contact lists, etc.
* <code>&nbsp;25273</code> ![](https://img.shields.io/github/last-commit/select2/select2) [select2](https://github.com/select2/select2) - a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.
* <code>&nbsp;22095</code> ![](https://img.shields.io/github/last-commit/harvesthq/chosen) [chosen](https://github.com/harvesthq/chosen) - A library for making long, unwieldy select boxes more friendly.

### File Uploader

* <code>&nbsp;31084</code> ![](https://img.shields.io/github/last-commit/blueimp/jQuery-File-Upload) [jQuery-File-Upload](https://github.com/blueimp/jQuery-File-Upload) - File Upload widget with multiple file selection, drag&amp;drop support, progress bar, validation and preview images, audio and video for jQuery.
* <code>&nbsp;16439</code> ![](https://img.shields.io/github/last-commit/enyo/dropzone) [dropzone](https://github.com/enyo/dropzone) - Dropzone is an easy to use drag'n'drop library. It supports image previews and shows nice progress bars.
* <code>&nbsp;&nbsp;2848</code> ![](https://img.shields.io/github/last-commit/flowjs/flow.js) [flow.js](https://github.com/flowjs/flow.js) - A JavaScript library providing multiple simultaneous, stable, fault-tolerant and resumable/restartable file uploads via the HTML5 File API.
* <code>&nbsp;&nbsp;8168</code> ![](https://img.shields.io/github/last-commit/FineUploader/fine-uploader) [fine-uploader](https://github.com/FineUploader/fine-uploader) - Multiple file upload plugin with progress-bar, drag-and-drop, direct-to-S3 uploading.
* <code>&nbsp;&nbsp;3581</code> ![](https://img.shields.io/github/last-commit/mailru/FileAPI) [FileAPI](https://github.com/mailru/FileAPI) - A set of JavaScript tools for working with files. Multiupload, drag'n'drop and chunked file upload. Images: crop, resize and auto orientation by EXIF.
* <code>&nbsp;&nbsp;5529</code> ![](https://img.shields.io/github/last-commit/moxiecode/plupload) [plupload](https://github.com/moxiecode/plupload) - A JavaScript API for dealing with file uploads it supports features like multiple file selection, file type filtering, request chunking, client side image scaling and it uses different runtimes to achieve this such as HTML 5, Silverlight and Flash.
* <code>&nbsp;12365</code> ![](https://img.shields.io/github/last-commit/pqina/filepond) [filepond](https://github.com/pqina/filepond) - A JavaScript library that can upload anything you throw at it, optimizes images for faster uploads, and offers a great, accessible, silky smooth user experience.

### Other

* <code>&nbsp;&nbsp;5138</code> ![](https://img.shields.io/github/last-commit/jquery-form/form) [form](https://github.com/jquery-form/form) - jQuery Form Plugin.
* <code>&nbsp;&nbsp;2371</code> ![](https://img.shields.io/github/last-commit/guillaumepotier/Garlic.js) [Garlic.js](https://github.com/guillaumepotier/Garlic.js) - Automatically persist your forms' text and select field values locally, until the form is submitted.
* <code>&nbsp;&nbsp;1625</code> ![](https://img.shields.io/github/last-commit/RadLikeWhoa/Countable) [Countable](https://github.com/RadLikeWhoa/Countable) - A JavaScript function to add live paragraph-, word- and character-counting to an HTML element.
* <code>&nbsp;11415</code> ![](https://img.shields.io/github/last-commit/jessepollak/card) [card](https://github.com/jessepollak/card) - Make your credit card form better in one line of code.
* <code>&nbsp;&nbsp;1266</code> ![](https://img.shields.io/github/last-commit/LeaVerou/stretchy) [stretchy](https://github.com/LeaVerou/stretchy) - Form element autosizing, the way it should be.
* <code>&nbsp;&nbsp;1591</code> ![](https://img.shields.io/github/last-commit/davidwells/analytics) [analytics](https://github.com/davidwells/analytics) - A lightweight, extendable analytics library designed to work with any third-party analytics provider to track page views, custom events, & identify users.
* <code>&nbsp;&nbsp;6107</code> ![](https://img.shields.io/github/last-commit/dataarts/dat.gui) [dat.GUI](https://github.com/dataarts/dat.gui) - A lightweight gui controller for changing variables in JavaScript.
## Tips

* <code>&nbsp;&nbsp;2032</code> ![](https://img.shields.io/github/last-commit/jaz303/tipsy) [tipsy](https://github.com/jaz303/tipsy) - Facebook-style tooltips plugin for jQuery.
* <code>&nbsp;&nbsp;1259</code> ![](https://img.shields.io/github/last-commit/enyo/opentip) [opentip](https://github.com/enyo/opentip) - An open source JavaScript tooltip based on the prototype framework.
* <code>&nbsp;&nbsp;2011</code> ![](https://img.shields.io/github/last-commit/qTip2/qTip2) [qTip2](https://github.com/qTip2/qTip2) - Pretty powerful tooltips.
* <code>&nbsp;&nbsp;2767</code> ![](https://img.shields.io/github/last-commit/iamceege/tooltipster) [tooltipster](https://github.com/iamceege/tooltipster) - A jQuery tooltip plugin.
* <code>&nbsp;&nbsp;&nbsp;651</code> ![](https://img.shields.io/github/last-commit/arashmanteghi/simptip) [simptip](https://github.com/arashmanteghi/simptip) - A simple CSS tooltip made with Sass.
* <code>&nbsp;&nbsp;2325</code> ![](https://img.shields.io/github/last-commit/paulkinzett/toolbar) [toolbar](https://github.com/paulkinzett/toolbar) - A tooltip style toolbar jQuery plugin
* <code>&nbsp;&nbsp;8221</code> ![](https://img.shields.io/github/last-commit/chinchang/hint.css) [hint.css](https://github.com/chinchang/hint.css) - A tooltip library in CSS for your lovely websites.

## Modals and Popups

* <code>&nbsp;11255</code> ![](https://img.shields.io/github/last-commit/dimsemenov/Magnific-Popup) [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) - Light and responsive lightbox script with focus on performance.
* <code>&nbsp;&nbsp;&nbsp;429</code> ![](https://img.shields.io/github/last-commit/gristmill/jquery-popbox) [jquery-popbox](https://github.com/gristmill/jquery-popbox) - jQuery PopBox UI Element.
* <code>&nbsp;&nbsp;1780</code> ![](https://img.shields.io/github/last-commit/voronianski/jquery.avgrund.js) [jquery.avgrund.js](https://github.com/voronianski/jquery.avgrund.js) - A jQuery plugin with new modal concept for popups.
* <code>&nbsp;&nbsp;6941</code> ![](https://img.shields.io/github/last-commit/HubSpot/vex) [vex](https://github.com/HubSpot/vex) - A modern dialog library which is highly configurable and easy to style.
* <code>&nbsp;&nbsp;5036</code> ![](https://img.shields.io/github/last-commit/jschr/bootstrap-modal) [bootstrap-modal](https://github.com/jschr/bootstrap-modal) - Extends the default Bootstrap Modal class. Responsive, stackable, ajax and more.
* <code>&nbsp;&nbsp;1826</code> ![](https://img.shields.io/github/last-commit/drublic/css-modal) [css-modal](https://github.com/drublic/css-modal) - A modal built out of pure CSS.
* <code>&nbsp;&nbsp;&nbsp;514</code> ![](https://img.shields.io/github/last-commit/vast-engineering/jquery-popup-overlay) [jquery-popup-overlay](https://github.com/vast-engineering/jquery-popup-overlay) - jQuery plugin for responsive and accessible modal windows and tooltips.
* <code>&nbsp;21977</code> ![](https://img.shields.io/github/last-commit/t4t5/sweetalert) [SweetAlert](https://github.com/t4t5/sweetalert) - An awesome replacement for JavaScript's alert.
* <code>&nbsp;14413</code> ![](https://img.shields.io/github/last-commit/sweetalert2/sweetalert2) [SweetAlert2](https://github.com/sweetalert2/sweetalert2) - An awesome replacement for JavaScript's alert.
* <code>&nbsp;&nbsp;2279</code> ![](https://img.shields.io/github/last-commit/feimosi/baguetteBox.js) [baguetteBox.js](https://github.com/feimosi/baguetteBox.js) - Simple and easy to use lightbox script written in pure JavaScript.
* <code>&nbsp;&nbsp;4785</code> ![](https://img.shields.io/github/last-commit/jackmoore/colorbox) [colorbox](https://github.com/jackmoore/colorbox) - A light-weight, customizable lightbox plugin for jQuery.
* <code>&nbsp;&nbsp;7181</code> ![](https://img.shields.io/github/last-commit/fancyapps/fancyBox) [fancyBox](https://github.com/fancyapps/fancyBox) - A tool that offers a nice and elegant way to add zooming functionality for images, html content and multi-media on your webpages.
* <code>&nbsp;&nbsp;1972</code> ![](https://img.shields.io/github/last-commit/brutaldesign/swipebox) [swipebox](https://github.com/brutaldesign/swipebox) - A touchable jQuery lightbox
* <code>&nbsp;&nbsp;1325</code> ![](https://img.shields.io/github/last-commit/StephanWagner/jBox) [jBox](https://github.com/StephanWagner/jBox) - jBox is a powerful and flexible jQuery plugin, taking care of all your popup windows, tooltips, notices and more.
* <code>&nbsp;&nbsp;5067</code> ![](https://img.shields.io/github/last-commit/sachinchoolur/lightGallery) [lightGallery](https://github.com/sachinchoolur/lightGallery) - A customizable, modular, responsive, lightbox gallery plugin for jQuery.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;14</code> ![](https://img.shields.io/github/last-commit/Alexandrshy/keukenhof) [keukenhof](https://github.com/Alexandrshy/keukenhof) - Lightweight, no dependencies, accessibility enabled TypeScript library for creating modal windows.
* <code>&nbsp;&nbsp;6437</code> ![](https://img.shields.io/github/last-commit/sindresorhus/screenfull.js) [screenfull.js](https://github.com/sindresorhus/screenfull.js) - the JavaScript Fullscreen API, which lets you bring the page or any element into fullscreen. Smoothens out the browser implementation differences, so you don't have to.

## Scroll

* <code>&nbsp;&nbsp;3273</code> ![](https://img.shields.io/github/last-commit/stutrek/scrollMonitor) [scrollMonitor](https://github.com/stutrek/scrollMonitor) - A simple and fast API to monitor elements as you scroll.
* <code>&nbsp;10839</code> ![](https://img.shields.io/github/last-commit/WickyNilliams/headroom.js) [headroom](https://github.com/WickyNilliams/headroom.js) - Give your pages some headroom. Hide your header until you need it.
* <code>&nbsp;&nbsp;9553</code> ![](https://img.shields.io/github/last-commit/peachananr/onepage-scroll) [onepage-scroll](https://github.com/peachananr/onepage-scroll) - Create an Apple-like one page scroller website (iPhone 5S website) with One Page Scroll plugin.
* <code>&nbsp;12820</code> ![](https://img.shields.io/github/last-commit/cubiq/iscroll) [iscroll](https://github.com/cubiq/iscroll) - iScroll is a high performance, small footprint, dependency free, multi-platform JavaScript scroller.
* <code>&nbsp;18550</code> ![](https://img.shields.io/github/last-commit/Prinzhorn/skrollr) [skrollr](https://github.com/Prinzhorn/skrollr) - Stand-alone parallax scrolling library for mobile (Android + iOS) and desktop. No jQuery.
* <code>&nbsp;15680</code> ![](https://img.shields.io/github/last-commit/wagerfield/parallax) [parallax](https://github.com/wagerfield/parallax) - Parallax Engine that reacts to the orientation of a smart device.
* <code>&nbsp;&nbsp;4633</code> ![](https://img.shields.io/github/last-commit/markdalgleish/stellar.js) [stellar.js](https://github.com/markdalgleish/stellar.js) - Parallax scrolling made easy.
* <code>&nbsp;&nbsp;2306</code> ![](https://img.shields.io/github/last-commit/cameronmcefee/plax) [plax](https://github.com/cameronmcefee/plax) - jQuery powered parallaxing.
* <code>&nbsp;&nbsp;1150</code> ![](https://img.shields.io/github/last-commit/stephband/jparallax) [jparallax](https://github.com/stephband/jparallax) - jQuery plugin for creating interactive parallax effect.
* <code>&nbsp;33434</code> ![](https://img.shields.io/github/last-commit/alvarotrigo/fullPage.js) [fullPage](https://github.com/alvarotrigo/fullPage.js) - A simple and easy to use plugin to create fullscreen scrolling websites (also known as single page websites).
* <code>&nbsp;&nbsp;&nbsp;205</code> ![](https://img.shields.io/github/last-commit/s-yadav/ScrollMenu) [ScrollMenu](https://github.com/s-yadav/ScrollMenu) - A new interface to replace old boring scrollbar.
* <code>&nbsp;&nbsp;7030</code> ![](https://img.shields.io/github/last-commit/NeXTs/Clusterize.js) [Clusterize.js](https://github.com/NeXTs/Clusterize.js) - Tiny vanilla JS plugin to display large data sets easily.
* <code>&nbsp;&nbsp;1393</code> ![](https://img.shields.io/github/last-commit/geosigno/simpleParallax) [simpleParallax](https://github.com/geosigno/simpleParallax) - Simple and tiny JavaScript library to add parallax animations on any images
* <code>&nbsp;&nbsp;6435</code> ![](https://img.shields.io/github/last-commit/dixonandmoe/rellax) [rellax](https://github.com/dixonandmoe/rellax) - Buttery smooth, super lightweight, vanilla javascript parallax library.
* <code>&nbsp;&nbsp;&nbsp;733</code> ![](https://img.shields.io/github/last-commit/ashthornton/asscroll) [asscroll](https://github.com/ashthornton/asscroll) - A hybrid smooth scroll setup that combines the performance gains of virtual scroll with the reliability of native scroll.
* <code>&nbsp;&nbsp;4336</code> ![](https://img.shields.io/github/last-commit/hakimel/stroll.js) [stroll](https://github.com/hakimel/stroll.js) - A collection of CSS List scroll effects bind to dom through javascript.
* <code>&nbsp;&nbsp;4842</code> ![](https://img.shields.io/github/last-commit/locomotivemtl/locomotive-scroll) [locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) - Detects the elements in viewport and smooth scrolling with parallax.
* <code>&nbsp;&nbsp;6511</code> ![](https://img.shields.io/github/last-commit/tholman/elevator.js) [elevator.js](https://github.com/tholman/elevator.js) - Finally, a "back to top" button that behaves like a real elevator.

## Menu

* <code>&nbsp;&nbsp;7720</code> ![](https://img.shields.io/github/last-commit/kamens/jQuery-menu-aim) [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - jQuery plugin to fire events when user's cursor aims at particular dropdown menu items. For making responsive mega dropdowns like Amazon's.
* <code>&nbsp;&nbsp;2157</code> ![](https://img.shields.io/github/last-commit/swisnl/jQuery-contextMenu) [jQuery contextMenu](https://github.com/swisnl/jQuery-contextMenu) - contextMenu manager.
* <code>&nbsp;&nbsp;7981</code> ![](https://img.shields.io/github/last-commit/mango/slideout) [Slideout](https://github.com/mango/slideout) - A responsive touch slideout navigation menu for mobile web apps.
* <code>&nbsp;&nbsp;&nbsp;135</code> ![](https://img.shields.io/github/last-commit/JoanClaret/slide-and-swipe-menu) [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) - A sliding swipe menu that works with touchSwipe library.
* <code>&nbsp;&nbsp;2550</code> ![](https://img.shields.io/github/last-commit/FrDH/jQuery.mmenu) [mmenu](https://github.com/FrDH/jQuery.mmenu) - The best jQuery plugin for app look-alike on- and off-canvas menus with sliding submenus for your website and webapp.


## Table/Grid

* <code>&nbsp;&nbsp;1066</code> ![](https://img.shields.io/github/last-commit/hikalkan/jtable) [jTable](https://github.com/hikalkan/jtable) - A jQuery plugin to create AJAX based CRUD tables.
* [DataTables](https://www.datatables.net/) - (jQuery plug-in) It is a highly flexible tool, based upon the foundations of progressive enhancement, and will add advanced interaction controls to any HTML table.
* [Tabulator](http://olifolkerd.github.io/tabulator/) - (jQuery plug-in) An extremely flexible library that create tables with a range of interactive features from any JSON data source or existing HTML table.
* [Bootstrap Table](https://bootstrap-table.com/) - An Extension to the popular Bootstrap framework for creating tables that fit the style of your site with no need for additional markup.
* <code>&nbsp;&nbsp;1209</code> ![](https://img.shields.io/github/last-commit/mkoryak/floatThead) [floatThead](https://github.com/mkoryak/floatThead) - (jQuery plug-in) lock any table's header while scrolling within the body. Works on any table and requires no custom html or css.
* [Masonry](https://masonry.desandro.com/) - A cascading grid layout library.
* [Packery](https://packery.metafizzy.co/) - A grid layout library that uses a bin-packing algorithm. Useable for draggable layouts.
* [Isotope](https://isotope.metafizzy.co/) - A filterable, sortable, grid layout library. Can implement Masonry, Packery, and other layouts.
* <code>&nbsp;&nbsp;9324</code> ![](https://img.shields.io/github/last-commit/kristoferjoseph/flexboxgrid) [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) - Grid based on CSS3 flexbox.
* <code>&nbsp;&nbsp;5969</code> ![](https://img.shields.io/github/last-commit/jspreadsheet/ce) [Jspreadsheet](https://github.com/jspreadsheet/ce) - Jspreadsheet is a lightweight vanilla javascript plugin to create amazing web-based interactive tables and spreadsheets compatible with other spreadsheet software.

## Frameworks

* [Semantic UI](https://semantic-ui.com/) - UI Kit with lots of themes and elements.
* [w2ui](http://w2ui.com/) - A set of jQuery plugins for front-end development of data-driven web applications.
* <code>&nbsp;&nbsp;1099</code> ![](https://img.shields.io/github/last-commit/mrmrs/fluidity) [fluidity](https://github.com/mrmrs/fluidity) - The worlds smallest fully-responsive css framework.
* <code>&nbsp;&nbsp;1911</code> ![](https://img.shields.io/github/last-commit/sapo/Ink) [Ink](https://github.com/sapo/Ink) - An HTML5/CSS3 framework used at SAPO for fast and efficient website design and prototyping.
* <code>&nbsp;&nbsp;&nbsp;134</code> ![](https://img.shields.io/github/last-commit/dataformsjs/dataformsjs) [DataFormsJS](https://github.com/dataformsjs/dataformsjs) - A minimal JavaScript Framework and standalone components for rapid development of sites and SPA's.
* <code>&nbsp;&nbsp;&nbsp;166</code> ![](https://img.shields.io/github/last-commit/Guseyn/EHTML) [EHTML](https://github.com/Guseyn/EHTML) - HTML Framework that allows you not to write JavaScript code.

## Boilerplates

 * <code>&nbsp;52637</code> ![](https://img.shields.io/github/last-commit/h5bp/html5-boilerplate) [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) - A professional front-end template for building fast, robust, and adaptable web apps or sites.
 * <code>&nbsp;&nbsp;3904</code> ![](https://img.shields.io/github/last-commit/h5bp/mobile-boilerplate) [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) - A front-end template that helps you build fast, modern mobile web apps.
 * <code>&nbsp;&nbsp;&nbsp;562</code> ![](https://img.shields.io/github/last-commit/chrishumboldt/webplate) [webplate](https://github.com/chrishumboldt/webplate) - An awesome front-end framework that lets you stay focused on building your site or app while remaining really easy to use.
 * <code>&nbsp;&nbsp;4447</code> ![](https://img.shields.io/github/last-commit/TedGoas/Cerberus) [Cerberus](https://github.com/TedGoas/Cerberus) - A few simple, but solid patterns for responsive HTML emails. Even in Outlook.
 * <code>&nbsp;&nbsp;&nbsp;&nbsp;43</code> ![](https://img.shields.io/github/last-commit/CodyHouse/full-page-intro-and-navigation) [full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) - An intro page with a full width background image, a bold animated menu and an iOS-like blurred effect behind the navigation.
 * <code>&nbsp;&nbsp;&nbsp;&nbsp;31</code> ![](https://img.shields.io/github/last-commit/crozynski/Fluid-Squares) [Fluid-Squares](https://github.com/crozynski/Fluid-Squares) - A fluid grid of square units.
 * <code>&nbsp;&nbsp;&nbsp;&nbsp;67</code> ![](https://img.shields.io/github/last-commit/bradfrost/Mobile-First-RWD) [Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) - An example of a mobile-first responsive web design.
 * <code>&nbsp;&nbsp;1580</code> ![](https://img.shields.io/github/last-commit/bradfrost/this-is-responsive) [this-is-responsive](https://github.com/bradfrost/this-is-responsive) - This Is Responsive.
 * [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) Task automation with NPM run-scripts.

## Images

 * <code>&nbsp;&nbsp;1408</code> ![](https://img.shields.io/github/last-commit/imgix/drift) [Drift](https://github.com/imgix/drift) - Easily add "zoom on hover" functionality to your site's images. Lightweight, no-dependency JavaScript.
 * <code>&nbsp;&nbsp;&nbsp;159</code> ![](https://img.shields.io/github/last-commit/AndersDJohnson/magnificent.js) [Magnificent.js](https://github.com/AndersDJohnson/magnificent.js) - Zoom responsively, images & more, w/ jQuery.
 * <code>&nbsp;&nbsp;2245</code> ![](https://img.shields.io/github/last-commit/pchen66/panolens.js) [Panolens.js](https://github.com/pchen66/panolens.js) - Panolens.js is an event-driven and WebGL based panorama viewer. Lightweight and flexible
## Gesture

* <code>&nbsp;22970</code> ![](https://img.shields.io/github/last-commit/hammerjs/hammer.js) [hammer.js](https://github.com/hammerjs/hammer.js) - A JavaScript library for multi-touch gestures.
* <code>&nbsp;&nbsp;&nbsp;320</code> ![](https://img.shields.io/github/last-commit/hammerjs/touchemulator) [touchemulator](https://github.com/hammerjs/touchemulator) - Emulate touch input on your desktop.
* <code>&nbsp;21144</code> ![](https://img.shields.io/github/last-commit/bevacqua/dragula) [Dragula](https://github.com/bevacqua/dragula/) - Drag and drop so simple it hurts.


## Maps

* <code>&nbsp;33598</code> ![](https://img.shields.io/github/last-commit/Leaflet/Leaflet) [Leaflet](https://github.com/Leaflet/Leaflet) - JavaScript library for mobile-friendly interactive maps.
* <code>&nbsp;&nbsp;8532</code> ![](https://img.shields.io/github/last-commit/AnalyticalGraphicsInc/cesium) [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - Open Source WebGL virtual globe and map engine.
* <code>&nbsp;&nbsp;7115</code> ![](https://img.shields.io/github/last-commit/HPNeo/gmaps) [gmaps](https://github.com/HPNeo/gmaps) - The easiest way to use Google Maps.
* <code>&nbsp;&nbsp;1578</code> ![](https://img.shields.io/github/last-commit/simplegeo/polymaps) [polymaps](https://github.com/simplegeo/polymaps) - A free JavaScript library for making dynamic, interactive maps in modern web browsers.
* <code>&nbsp;&nbsp;1523</code> ![](https://img.shields.io/github/last-commit/kartograph/kartograph.js) [kartograph.js](https://github.com/kartograph/kartograph.js) - Open source JavaScript renderer for Kartograph SVG maps.
* <code>&nbsp;&nbsp;1845</code> ![](https://img.shields.io/github/last-commit/mapbox/mapbox.js) [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, a Leaflet Plugin.
* <code>&nbsp;&nbsp;1793</code> ![](https://img.shields.io/github/last-commit/manifestinteractive/jqvmap) [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery Vector Map Library.
* [OpenLayers3](https://openlayers.org/) - A high-performance, feature-packed library for all your mapping needs.
* <code>&nbsp;&nbsp;3378</code> ![](https://img.shields.io/github/last-commit/uber/h3) [H3js](https://github.com/uber/h3) - Hexagonal hierarchical geospatial indexing system ported to javascript by Uber for geospatial visualization.

## Video/Audio

 * <code>&nbsp;&nbsp;1076</code> ![](https://img.shields.io/github/last-commit/mike-zarandona/prettyembed.js) [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) - Prettier embeds for your YouTubes - with nice options like high-res preview images, advanced customization of embed options, and optional FitVids support.
 * <code>&nbsp;&nbsp;1275</code> ![](https://img.shields.io/github/last-commit/etianen/html5media) [html5media](https://github.com/etianen/html5media) - Enables <video> and <audio> tags in all major browsers. <https://html5media.info/>
 * <code>&nbsp;&nbsp;&nbsp;&nbsp;88</code> ![](https://img.shields.io/github/last-commit/adrienjoly/playemjs) [Play-em JS](https://github.com/adrienjoly/playemjs) - Play'em is a JavaScript component that manages a music/video track queue and plays a sequence of songs by embedding several players in a HTML DIV including Youtube, Soundcloud and Vimeo.
 * <code>&nbsp;&nbsp;&nbsp;&nbsp;40</code> ![](https://img.shields.io/github/last-commit/Acconut/polyplayer) [polyplayer](https://github.com/Acconut/polyplayer) - Rule YouTube, Soundcloud and Vimeo player with one API.
 * <code>&nbsp;&nbsp;1895</code> ![](https://img.shields.io/github/last-commit/flowplayer/flowplayer) [flowplayer](https://github.com/flowplayer/flowplayer) - The HTML5 video player for the web
 <https://flowplayer.com/>
 * <code>&nbsp;&nbsp;7815</code> ![](https://img.shields.io/github/last-commit/johndyer/mediaelement) [mediaelement](https://github.com/johndyer/mediaelement) - HTML5 <audio> or <video> player with Flash and Silverlight shims that mimics the HTML5 MediaElement API, enabling a consistent UI in all browsers. <http://www.mediaelementjs.com/>
 * <code>&nbsp;&nbsp;4195</code> ![](https://img.shields.io/github/last-commit/CreateJS/SoundJS) [SoundJS](https://github.com/CreateJS/SoundJS) - A library to make working with audio on the web easier. It provides a consistent API for playing audio in different browsers.
 * <code>&nbsp;33133</code> ![](https://img.shields.io/github/last-commit/videojs/video.js) [video.js](https://github.com/videojs/video.js) - Video.js - open source HTML5 & Flash video player.
 * <code>&nbsp;&nbsp;4802</code> ![](https://img.shields.io/github/last-commit/davatron5000/FitVids.js) [FitVids.js](https://github.com/davatron5000/FitVids.js) - A lightweight, easy-to-use jQuery plugin for fluid width video embeds.
 * <code>&nbsp;&nbsp;&nbsp;700</code> ![](https://img.shields.io/github/last-commit/IonDen/ion.sound) [Ion.Sound](https://github.com/IonDen/ion.sound) - Simple sounds on any web page.
 * <code>&nbsp;&nbsp;&nbsp;576</code> ![](https://img.shields.io/github/last-commit/WolframHempel/photobooth-js) [photobooth-js](https://github.com/WolframHempel/photobooth-js) - A widget that allows users to take their avatar pictures on your site.
 * <code>&nbsp;&nbsp;5654</code> ![](https://img.shields.io/github/last-commit/clappr/clappr) [clappr](https://github.com/clappr/clappr) - An extensible media player for the web http://clappr.io
 * <code>&nbsp;&nbsp;&nbsp;646</code> ![](https://img.shields.io/github/last-commit/MikeKovarik/exifr) [exifr](https://github.com/MikeKovarik/exifr) - The fastest and most versatile EXIF reading library. https://mutiny.cz/exifr/
 * <code>&nbsp;&nbsp;&nbsp;259</code> ![](https://img.shields.io/github/last-commit/EvandroLG/ts-audio) [ts-audio](https://github.com/EvandroLG/ts-audio) - an agnostic and easy-to-use library to work with the `AudioContext` API.
 * [AmplitudeJS](https://521dimensions.com/open-source/amplitudejs) - Open Source HTML5 Web Audio Library. Design your web audio player, the way you want. No dependencies required.
 * <code>&nbsp;&nbsp;&nbsp;633</code> ![](https://img.shields.io/github/last-commit/ysulyma/ractive-player) [ractive-player](https://github.com/ysulyma/ractive-player) - A library for making interactive videos in React.js.
 * <code>&nbsp;&nbsp;2607</code> ![](https://img.shields.io/github/last-commit/Kagami/ffmpeg.js) [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) - FFmpeg optimized for in-browser use: minimal size for faster loading, asm.js, performance tunings, etc.
 * <code>&nbsp;20991</code> ![](https://img.shields.io/github/last-commit/bilibili/flv.js) [flv.js](https://github.com/bilibili/flv.js) - An HTML5 Flash Video (FLV) Player written in pure JavaScript without Flash.
 * <code>&nbsp;11230</code> ![](https://img.shields.io/github/last-commit/video-dev/hls.js) [hls.js](https://github.com/video-dev/hls.js) -  A JavaScript library that implements an HTTP Live Streaming client. It relies on HTML5 video and MediaSource Extensions for playback.

## Typography

 * <code>&nbsp;&nbsp;4619</code> ![](https://img.shields.io/github/last-commit/simplefocus/FlowType.JS) [FlowType.JS](https://github.com/simplefocus/FlowType.JS) - Web typography at its finest: font-size and line-height based on element width.
 * <code>&nbsp;&nbsp;&nbsp;881</code> ![](https://img.shields.io/github/last-commit/zachleat/BigText) [BigText](https://github.com/zachleat/BigText) - jQuery plugin, calculates the font-size and word-spacing needed to match a line of text to a specific width.
 * <code>&nbsp;&nbsp;&nbsp;589</code> ![](https://img.shields.io/github/last-commit/peterhry/circletype) [circletype](https://github.com/peterhry/circletype) - A jQuery plugin that lets you curve type on the web.
 * <code>&nbsp;&nbsp;1338</code> ![](https://img.shields.io/github/last-commit/freqDec/slabText) [slabText](https://github.com/freqDec/slabText/) - A jQuery plugin for producing big, bold & responsive headlines.
 * <code>&nbsp;&nbsp;&nbsp;756</code> ![](https://img.shields.io/github/last-commit/peachananr/simple-text-rotator) [simple-text-rotator](https://github.com/peachananr/simple-text-rotator) - Add a super simple rotating text to your website with little to no markup.
 * <code>&nbsp;&nbsp;&nbsp;185</code> ![](https://img.shields.io/github/last-commit/chuckyglitch/novacancy.js) [novacancy.js](https://github.com/chuckyglitch/novacancy.js) - Text Neon Golden effect jQuery plug-in.
 * <code>&nbsp;&nbsp;&nbsp;124</code> ![](https://img.shields.io/github/last-commit/ghepting/jquery-responsive-text) [jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) - Make your text sizing responsive!
 * <code>&nbsp;&nbsp;6761</code> ![](https://img.shields.io/github/last-commit/davatron5000/FitText.js) [FitText.js](https://github.com/davatron5000/FitText.js) - A jQuery plugin for inflating web type.
 * <code>&nbsp;&nbsp;5381</code> ![](https://img.shields.io/github/last-commit/davatron5000/Lettering.js) [Lettering.js](https://github.com/davatron5000/Lettering.js) - A lightweight, easy to use JavaScript `<span>` injector for radical Web Typography.


## Animations

* <code>&nbsp;17141</code> ![](https://img.shields.io/github/last-commit/julianshapiro/velocity) [velocity](https://github.com/julianshapiro/velocity) - Accelerated JavaScript animation.
* <code>&nbsp;&nbsp;7385</code> ![](https://img.shields.io/github/last-commit/rstacruz/jquery.transit) [jquery.transit](https://github.com/rstacruz/jquery.transit) - Super-smooth CSS3 transformations and transitions for jQuery.
* <code>&nbsp;&nbsp;6229</code> ![](https://img.shields.io/github/last-commit/tictail/bounce.js) [bounce.js](https://github.com/tictail/bounce.js) - Create tasty CSS3 powered animations in no time.
* <code>&nbsp;13968</code> ![](https://img.shields.io/github/last-commit/greensock/GreenSock-JS) [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - High-performance HTML5 animations that work in all major browsers.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;95</code> ![](https://img.shields.io/github/last-commit/EvandroLG/transitionEnd) [TransitionEnd](https://github.com/EvandroLG/transitionEnd) - TransitionEnd is an agnostic and cross-browser library to work with transitioned event.
* <code>&nbsp;&nbsp;7441</code> ![](https://img.shields.io/github/last-commit/michaelvillar/dynamics.js) [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - JavaScript library to create physics-based CSS animations.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9</code> ![](https://img.shields.io/github/last-commit/pstadler/the-cube) [the-cube](https://github.com/pstadler/the-cube) - The Cube is an experiment with CSS3 transitions.
* <code>&nbsp;11032</code> ![](https://img.shields.io/github/last-commit/h5bp/Effeckt.css) [Effeckt.css](https://github.com/h5bp/Effeckt.css) - A Performant Transitions and Animations Library.
* <code>&nbsp;74263</code> ![](https://img.shields.io/github/last-commit/daneden/animate.css) [animate.css](https://github.com/daneden/animate.css) - A cross-browser library of CSS animations. As easy to use as an easy thing.
* <code>&nbsp;&nbsp;3601</code> ![](https://img.shields.io/github/last-commit/jschr/textillate) [textillate](https://github.com/jschr/textillate) - A simple plugin for CSS3 text animations.
* <code>&nbsp;&nbsp;4672</code> ![](https://img.shields.io/github/last-commit/visionmedia/move.js) [move.js](https://github.com/visionmedia/move.js) - CSS3 backed JavaScript animation framework.
* <code>&nbsp;&nbsp;2555</code> ![](https://img.shields.io/github/last-commit/LeaVerou/animatable) [animatable](https://github.com/LeaVerou/animatable) - One property, two values, endless possibilities.
* <code>&nbsp;&nbsp;&nbsp;209</code> ![](https://img.shields.io/github/last-commit/peachananr/shuffle-images) [shuffle-images](https://github.com/peachananr/shuffle-images) - The Simplest Way to shuffle through images in a Creative Way.
* <code>&nbsp;&nbsp;4454</code> ![](https://img.shields.io/github/last-commit/miguel-perez/smoothState.js) [smoothState.js](https://github.com/miguel-perez/smoothState.js) - Unobtrusive page transitions with jQuery.
* [Anime.js](https://animejs.com/) - A JavaScript animation engine.
* [Mo.js](http://mojs.io) - Motion graphics toolbelt for the web.
* <code>&nbsp;25666</code> ![](https://img.shields.io/github/last-commit/VincentGarreau/particles.js) [particles.js](https://github.com/VincentGarreau/particles.js) - A lightweight JavaScript library for creating particles.
* <code>&nbsp;&nbsp;3185</code> ![](https://img.shields.io/github/last-commit/matteobruni/tsparticles) [tsParticles](https://github.com/matteobruni/tsparticles) - A new and improved version of particles.js with bug fixes and many new features.
* <code>&nbsp;&nbsp;&nbsp;492</code> ![](https://img.shields.io/github/last-commit/lindelof/particles-bg) [particles-bg](https://github.com/lindelof/particles-bg) - A lightweight React particles animation background component.
* <code>&nbsp;&nbsp;9592</code> ![](https://img.shields.io/github/last-commit/barbajs/barba) [barbajs](https://github.com/barbajs/barba) - It helps you create fluid and smooth transitions between your website's pages.
* <code>&nbsp;&nbsp;1108</code> ![](https://img.shields.io/github/last-commit/camwiegert/typical) [typicaljs](https://github.com/camwiegert/typical) - Animated typing in ~400 bytes 🐡 of JavaScript

## Image Processing

* <code>&nbsp;&nbsp;&nbsp;520</code> ![](https://img.shields.io/github/last-commit/davidsonfellipe/lena.js) [lena.js](https://github.com/davidsonfellipe/lena.js) - A Library for image processing with filters and util functions.
* <code>&nbsp;&nbsp;3030</code> ![](https://img.shields.io/github/last-commit/nodeca/pica) [pica](https://github.com/nodeca/pica) - High quality image resize (with fast Lanczos filter, implemented in pure JS).
* <code>&nbsp;&nbsp;7808</code> ![](https://img.shields.io/github/last-commit/fengyuanchen/cropper) [cropper](https://github.com/fengyuanchen/cropper) - A simple jQuery image cropping plugin.

## ES6

* <code>&nbsp;28880</code> ![](https://img.shields.io/github/last-commit/lukehoban/es6features) [es6features](https://github.com/lukehoban/es6features) - Overview of ECMAScript 6 features.
* <code>&nbsp;&nbsp;6192</code> ![](https://img.shields.io/github/last-commit/rse/es6-features) [es6-features](https://github.com/rse/es6-features) - ECMAScript 6: Feature Overview & Comparison.
* <code>&nbsp;12797</code> ![](https://img.shields.io/github/last-commit/DrkSephy/es6-cheatsheet) [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] cheatsheet containing tips, tricks, best practices and code snippets.
* [ECMAScript 6 compatibility table](http://kangax.github.io/compat-table/es6/) - Compatibility tables for all ECMAScript 6 features on a variety of environments.
* <code>&nbsp;40718</code> ![](https://img.shields.io/github/last-commit/babel/babel) [Babel (Formerly 6to5)](https://github.com/babel/babel) - Turn ES6+ code into vanilla ES5 with no runtime.
* <code>&nbsp;&nbsp;8164</code> ![](https://img.shields.io/github/last-commit/google/traceur-compiler) [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.


## Generators

* <code>&nbsp;52700</code> ![](https://img.shields.io/github/last-commit/gatsbyjs/gatsby) [Gatsby.js](https://github.com/gatsbyjs/gatsby) - React-based static site generator.
* <code>&nbsp;&nbsp;8168</code> ![](https://img.shields.io/github/last-commit/gridsome/gridsome) [Gridsome](https://github.com/gridsome/gridsome) - Vue-powered static site generator.
* <code>&nbsp;32419</code> ![](https://img.shields.io/github/last-commit/facebook/docusaurus) [Docusaurus](https://github.com/facebook/docusaurus) - React-based static site generator by Facebook, ideal for content-centric websites.

## SDK

* <code>&nbsp;&nbsp;1236</code> ![](https://img.shields.io/github/last-commit/huei90/javascript-sdk-design) [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - JavaScript SDK design guide extracted from work and personal experience.
* <code>&nbsp;&nbsp;&nbsp;217</code> ![](https://img.shields.io/github/last-commit/loverajoel/spotify-sdk) [Spotify SDK](https://github.com/loverajoel/spotify-sdk) - Entity oriented SDK to work with the Spotify Web API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;81</code> ![](https://img.shields.io/github/last-commit/square/connect-nodejs-sdk) [Square Node.js SDK](https://github.com/square/connect-nodejs-sdk/) - JavaScript client library for payments and other Square APIs.
 
## Full Text Search

* <code>&nbsp;&nbsp;8000</code> ![](https://img.shields.io/github/last-commit/olivernn/lunr.js) [lunr](https://github.com/olivernn/lunr.js) - Library for use in the browser and It indexes JSON documents and provides a simple search interface for retrieving documents that best match text queries.
* <code>&nbsp;&nbsp;8440</code> ![](https://img.shields.io/github/last-commit/nextapps-de/flexsearch) [flexsearch](https://github.com/nextapps-de/flexsearch) - It is a Next-Generation full text search library for Browser and Node.js.
* <code>&nbsp;&nbsp;1833</code> ![](https://img.shields.io/github/last-commit/weixsong/elasticlunr.js) [Elasticlunr](https://github.com/weixsong/elasticlunr.js) - This library is based on lunr.js, but more flexible and customized.
 
## Misc

* <code>&nbsp;&nbsp;3748</code> ![](https://img.shields.io/github/last-commit/toddmotto/echo) [echo](https://github.com/toddmotto/echo) - Lazy-loading images with data-* attributes.
* <code>&nbsp;10044</code> ![](https://img.shields.io/github/last-commit/scottjehl/picturefill) [picturefill](https://github.com/scottjehl/picturefill) - A responsive image polyfill for &lt;picture&gt;, srcset, sizes.
* <code>&nbsp;&nbsp;2992</code> ![](https://img.shields.io/github/last-commit/bestiejs/platform.js) [platform.js](https://github.com/bestiejs/platform.js) - A platform detection library that works on nearly all JavaScript platforms.
* <code>&nbsp;&nbsp;1029</code> ![](https://img.shields.io/github/last-commit/bestiejs/json3) [json3](https://github.com/bestiejs/json3) - A modern JSON implementation compatible with nearly all JavaScript platforms.
* [Logical Or Not](https://gabinaureche.com/logicalornot/) - A game about JavaScript specificities.
* <code>&nbsp;&nbsp;&nbsp;197</code> ![](https://img.shields.io/github/last-commit/infusion/BitSet.js) [BitSet.js](https://github.com/infusion/BitSet.js) - A JavaScript Bit-Vector implementation.
* <code>&nbsp;&nbsp;&nbsp;473</code> ![](https://img.shields.io/github/last-commit/joshbuddy/spoiler-alert) [spoiler-alert](https://github.com/joshbuddy/spoiler-alert) - SPOILER ALERT! A happy little jquery plugin to hide spoilers on your site.
* <code>&nbsp;&nbsp;&nbsp;140</code> ![](https://img.shields.io/github/last-commit/illyism/jquery.vibrate.js) [jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) - Vibration API Wrappers
* <code>&nbsp;10727</code> ![](https://img.shields.io/github/last-commit/javve/list.js) [list.js](https://github.com/javve/list.js) - Adds search, sort, filters and flexibility to tables, lists and various HTML elements. Built to be invisible and work on existing HTML.
https://listjs.com
* <code>&nbsp;&nbsp;4444</code> ![](https://img.shields.io/github/last-commit/patrickkunka/mixitup) [mixitup](https://github.com/patrickkunka/mixitup) - MixItUp - A Filter & Sort Plugin.
* <code>&nbsp;&nbsp;3559</code> ![](https://img.shields.io/github/last-commit/hootsuite/grid) [grid](https://github.com/hootsuite/grid) - Drag and drop library for two-dimensional, resizable and responsive lists.
* <code>&nbsp;&nbsp;3090</code> ![](https://img.shields.io/github/last-commit/liabru/jquery-match-height) [jquery-match-height](https://github.com/liabru/jquery-match-height) - a responsive equal heights plugin for jQuery.
* <code>&nbsp;&nbsp;3160</code> ![](https://img.shields.io/github/last-commit/surveyjs/survey-library) [SurveyJS](https://github.com/surveyjs/survey-library) - SurveyJS is a JavaScript Survey and Form Library. https://surveyjs.io/
* <code>&nbsp;&nbsp;2540</code> ![](https://img.shields.io/github/last-commit/sdras/array-explorer) [Array Explorer](https://github.com/sdras/array-explorer) and [Object Explorer](https://objectexplorer.netlify.app/) - Resources to help figure out what native JavaScript method would be best to use at any given time.
* [Clipboard.js](https://clipboardjs.com/) - "Copy to clipboard" without Flash or use of Frameworks.
* <code>&nbsp;&nbsp;7574</code> ![](https://img.shields.io/github/last-commit/sindresorhus/ky) [ky](https://github.com/sindresorhus/ky) - Tiny and elegant HTTP client based on the browser Fetch API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;70</code> ![](https://img.shields.io/github/last-commit/5anthosh/fcal) [Fcal](https://github.com/5anthosh/fcal) -  Math expression evaluator.
* <code>&nbsp;&nbsp;&nbsp;848</code> ![](https://img.shields.io/github/last-commit/joeattardi/emoji-button) [emoji-button](https://github.com/joeattardi/emoji-button) - Vanilla JavaScript emoji picker component.
* <code>&nbsp;&nbsp;&nbsp;119</code> ![](https://img.shields.io/github/last-commit/iooxa/article) [iooxa](https://github.com/iooxa/article) - Components for interactive scientific writing, reactive documents and explorable explanations.
* <code>&nbsp;&nbsp;1884</code> ![](https://img.shields.io/github/last-commit/idyll-lang/idyll) [Idyll](https://github.com/idyll-lang/idyll) - Create explorable explanations and interactive storytelling essays. Can be <code>&nbsp;&nbsp;&nbsp;&nbsp;12</code> ![](https://img.shields.io/github/last-commit/idyll-lang/idyll-embed) [embedded in HTML](https://github.com/idyll-lang/idyll-embed).
* <code>139083</code> ![](https://img.shields.io/github/last-commit/trekhleb/javascript-algorithms) [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) - Algorithms and data structures implemented in JavaScript with explanations and links to further readings.
* <code>&nbsp;16432</code> ![](https://img.shields.io/github/last-commit/fingerprintjs/fingerprintjs) [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) - Makes a visitor identifier from a browser fingerprint that stays the same in incognito mode and when browser data is purged.
* <code>&nbsp;&nbsp;4255</code> ![](https://img.shields.io/github/last-commit/pegjs/pegjs) [Peg.js](https://github.com/pegjs/pegjs) - A simple parser generator for JavaScript that produces fast parsers with excellent error reporting. Usable from your browser, from the command line, or via JavaScript API.
* <code>&nbsp;&nbsp;&nbsp;&nbsp;93</code> ![](https://img.shields.io/github/last-commit/ryanseys/lune) [lune](https://github.com/ryanseys/lune) - Library to calculate the phases of the moon accurately.
* <code>&nbsp;&nbsp;1501</code> ![](https://img.shields.io/github/last-commit/fcambus/jsemu) [jsemu](https://github.com/fcambus/jsemu) - A list of emulators written in the JavaScript programming language.

## Podcasts
* [JavaScript Air](https://javascriptair.com/) - The live video broadcast podcast all about JavaScript and the Web platform.
* [Web of Tomorrow](http://www.weboftomorrowpodcast.com/) - Podcast about JavaScript for beginners.
* [JavaScript Jabber](https://devchat.tv/show/javascript-jabber) - A weekly podcast about JavaScript, including Node.js, Front-End Technologies, Careers, Teams and more.

# Worth Reading

* <code>151997</code> ![](https://img.shields.io/github/last-commit/getify/You-Dont-Know-JS) [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) - Possibly the best book written on modern JavaScript, completely readable online for free, or can be bought to support the author.
* <code>&nbsp;&nbsp;8360</code> ![](https://img.shields.io/github/last-commit/braziljs/js-the-right-way) [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) - An easy-to-read, quick reference for JS best practices, accepted coding standards, and links around the Web.
* <code>&nbsp;&nbsp;2484</code> ![](https://img.shields.io/github/last-commit/revolunet/JSbooks) [JSbooks](https://github.com/revolunet/JSbooks) - Directory of free JavaScript ebooks.
* [Superhero.js](http://superherojs.com) - A collection of resources about creating, testing and maintaining a large JavaScript code base.
* <code>&nbsp;&nbsp;2241</code> ![](https://img.shields.io/github/last-commit/KittyGiraudel/SJSJ) [SJSJ](https://github.com/KittyGiraudel/SJSJ) - Simplified JavaScript Jargon is a community-driven attempt at explaining the loads of buzzwords making the current JavaScript ecosystem in a few simple words.
* <code>&nbsp;&nbsp;&nbsp;170</code> ![](https://img.shields.io/github/last-commit/sarbbottam/write-an-open-source-js-lib) [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) - A comprehensive guide through a set of steps to publish a JavaScript open source library.
* [JavaScript Tutorials](https://hackr.io/tutorials/learn-javascript) - Learn Javascript online from a diverse range of user ranked online tutorials.
* <code>&nbsp;15248</code> ![](https://img.shields.io/github/last-commit/getify/Functional-Light-JS) [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) - Pragmatic, balanced FP in JavaScript.
* <code>&nbsp;66150</code> ![](https://img.shields.io/github/last-commit/ryanmcdermott/clean-code-javascript) [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) - Clean Code concepts adapted for JavaScript.


# Other Awesome Lists
* <code>&nbsp;&nbsp;3654</code> ![](https://img.shields.io/github/last-commit/sotayamashita/awesome-css) [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css)
* <code>&nbsp;&nbsp;2045</code> ![](https://img.shields.io/github/last-commit/emijrp/awesome-awesome) [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome)
* <code>&nbsp;28785</code> ![](https://img.shields.io/github/last-commit/bayandin/awesome-awesomeness) [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness)
* <code>197555</code> ![](https://img.shields.io/github/last-commit/sindresorhus/awesome) [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
* <code>&nbsp;&nbsp;8029</code> ![](https://img.shields.io/github/last-commit/jnv/lists) [jnv/list](https://github.com/jnv/lists)
* <code>&nbsp;&nbsp;2470</code> ![](https://img.shields.io/github/last-commit/gianarb/awesome-angularjs) [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs)
* <code>&nbsp;&nbsp;&nbsp;&nbsp;75</code> ![](https://img.shields.io/github/last-commit/peterkokot/awesome-dojo) [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo)
* <code>&nbsp;&nbsp;3871</code> ![](https://img.shields.io/github/last-commit/addyosmani/es6-tools) [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools)
* <code>&nbsp;&nbsp;4583</code> ![](https://img.shields.io/github/last-commit/ericdouglas/ES6-Learning) [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning)
* <code>&nbsp;&nbsp;&nbsp;399</code> ![](https://img.shields.io/github/last-commit/obetomuniz/awesome-webcomponents) [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents)
* <code>&nbsp;&nbsp;4279</code> ![](https://img.shields.io/github/last-commit/willianjusten/awesome-svg) [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg)
* <code>&nbsp;&nbsp;7416</code> ![](https://img.shields.io/github/last-commit/davidsonfellipe/awesome-wpo) [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo)
* <code>&nbsp;&nbsp;&nbsp;400</code> ![](https://img.shields.io/github/last-commit/sadcitizen/awesome-backbone) [instanceofpro/awesome-backbone](https://github.com/sadcitizen/awesome-backbone)
* <code>&nbsp;47825</code> ![](https://img.shields.io/github/last-commit/enaqx/awesome-react) [enaqx/awesome-react](https://github.com/enaqx/awesome-react)
* <code>&nbsp;12779</code> ![](https://img.shields.io/github/last-commit/bolshchikov/js-must-watch) [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch)
* <code>&nbsp;&nbsp;&nbsp;811</code> ![](https://img.shields.io/github/last-commit/peterkokot/awesome-jquery) [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery)
* <code>&nbsp;&nbsp;&nbsp;141</code> ![](https://img.shields.io/github/last-commit/davidyezsetz/you-might-not-need-jquery-plugins) [davidyezsetz/you-might-not-need-jquery-plugins](https://github.com/davidyezsetz/you-might-not-need-jquery-plugins)
* <code>&nbsp;45910</code> ![](https://img.shields.io/github/last-commit/MaximAbramchuck/awesome-interview-questions) [MaximAbramchuck/awesome-interviews](https://github.com/MaximAbramchuck/awesome-interview-questions)
* <code>&nbsp;&nbsp;3448</code> ![](https://img.shields.io/github/last-commit/denolib/awesome-deno) [denolib/awesome-deno](https://github.com/denolib/awesome-deno)

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [chencheng](https://github.com/sorrycc) has waived all copyright and related or neighboring rights to this work.
