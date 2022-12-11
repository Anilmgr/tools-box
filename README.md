# Capacitor ToolsBox

The Capacitor ToolsBox is used to develop new features and verify bug fixes in Capacitor and the [official plugins](https://github.com/ionic-team/capacitor-plugins). It is built with [Ionic React](https://ionicframework.com/react).

## Setup

1. Fork and clone this repo.
2. Install the dependencies.

    ```shell
    npm install
    ```

The ToolsBox is just like any other Ionic Angular app. See [the docs](https://ionicframework.com/angular) to learn what you can do.

- `ionic build` to build web assets
- `ionic serve` to run web version in your browser
- `ionic cap sync`
- `ionic cap run <platform>` (also w/ livereload: just add `-l --external` flags)

You can also opt-out of the Ionic CLI and use npm scripts and the Capacitor CLI directly:

- `npm run build`
- `npm start`
- `npx cap sync`
- `npx cap run <platform>` (no automatic livereload)
