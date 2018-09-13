# Vscode Ember Snippets

Ember.js ES6, Ember Data & Handlebars snippets for Vscode editor. The credit of these
snippets [goes to this Atom package by mattmcmanus](https://github.com/mattmcmanus/atom-ember-snippets).

## Installation

- Press `F1`, paste `ext install vscode-ember-snippets` & then press `enter` (or)
- Goto extensions by pressing `Ctrl-Shift-X` (Windows/Linux) or `Cmd-Shift-X` (Mac) & Search for `Vscode Ember Snippets`, click on install

## Usage

Rather than listing everything out here, check out the snippet files themselves:

* [ember core snippets](snippets/ember.json) for:
  * Ember Objects
  * Routes
  * Components
  * Enumerables
  * Logger
  * Test
* ember rfc176 compliant imports*
  * *Note*: These imports require `ember-cli-babel@6.6.0` or higher
  * [application](snippets/import-application.json)
  * [array](snippets/import-array.json)
  * [base](snippets/import-base.json)
  * [component](snippets/import-component.json)
  * [controller](snippets/import-controller.json)
  * [debug](snippets/import-debug.json)
  * [ember-data](snippets/import-ember-data.json)
  * [engine](snippets/import-engine.json)
  * [map](snippets/import-map.json)
  * [object](snippets/import-object.json)
  * [polyfills](snippets/import-polyfills.json)
  * [routing](snippets/import-routing.json)
  * [rsvp](snippets/import-rsvp.json)
  * [runloop](snippets/import-runloop.json)
  * [service](snippets/import-service.json)
  * [string](snippets/import-string.json)
  * [test](snippets/import-test.json)
  * [utils](snippets/import-utils.json)
* [New file stubs](snippets/file-skeletons.json) for:
  * Routers, Components, Helpers & more
* [ember-data snippets](snippets/ember-data.json) for:
  * Store
  * Models
* [Handlebars](snippets/handlebars.json) for:
  * Default Helpers
  * Components

## Contributing

Please send PRs! I am sure there may be things I missed

### Third Party Snippets

In order to keep this package as focused and "lightweight" as possible. It has
been decided that it will focus on Ember snippets and it will not contain snippets
for various addons and/or third-party libraries.

You are more than welcomed to share your aggregated snippets using the list of
addon related snippets below.

### Non-Exhaustive List of Addon Related Snippets

* [Ember Data Factory Guy Snippets](https://github.com/Oreoz/atom-ember-data-factory-guy-snippets)

## Release Notes

### 1.0.0

Copied over the snippets that the original plugin uses, with some fixes

### 1.1.0

Lower VS code version requirements

### 1.1.1

Adding to readme the missing ember-data
