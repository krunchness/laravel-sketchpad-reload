# Sketchpad Reload

## Overview

Sketchpad Reload is Node module that provides file watching and live-reloading capability for [Laravel Sketchpad](https://github.com/davestewart/laravel-sketchpad).

By default it:

- watches all controller, asset and view folders
- reloads changes to loaded scripts and styles
- re-runs the current method if the controller is updated
- re-runs the current method when additionally-watched files are updated, added or deleted
- reloads the navigation when any controllers updated, added or deleted

Sketchpad Reload also runs as a standalone script – no need to integrate with any build processes!

## Express setup

If you have a standard Laravel setup, install Sketchpad Reload to your root folder:

```text
npm install sketchpad-reload --save
echo "require('sketchpad-reload')().watch()" > sketchpad.js
```

Once installed, run with a simple call: 

```text
node sketchpad
```

See the [wiki](https://github.com/davestewart/laravel-sketchpad-reload/wiki) for custom installation and setup instructions.
