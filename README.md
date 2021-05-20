# OpenSeadragonFabricjsOverlay

This package is a forked version of https://github.com/altert/OpenseadragonFabricjsOverlay

Please visit the original repository for details.

## Differences in forked version

This forked version does a few things differently.

- Syncs Fabric JS object zoom levels to OpenSeadragon's image zoom level, instead of the viewport zoom level. Basically this better supports browser resizing, both horizontally and vertically.
- This package provides JS module exports for `initFabricJSOverlay` and `fabric`, so you can `@import` into your compiled JS app.
