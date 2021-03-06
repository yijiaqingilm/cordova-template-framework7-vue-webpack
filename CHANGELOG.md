## 07.04.2017 - 1.0.11
* Fixed Device_router.html has been made compatible with Android < 4.4.0.
* Fixed key to vue lists
> Thanks for **konstantin-popov** for fixes.
* Added .editorconfig and files edited with this config.

## 14.03.2017 - 1.0.10
* Added epipebomb for linux and mac os.
* Fixed webpack ^2.2.1 support
* Fixed buffer size for webpack outputs
* Updated uglify js version to latest (for ES6 features)

## 17.01.2017 - 1.0.4
* Dev-server supports hot-module-replacement now!

## 16.01.2017 - 1.0.1
* Supports phonegap now!
* Template now uses `webpack-dev-server` for live-reload. So cordova-plugin-browsersync dependency dropped.
* `webpack-dev-server` dependency added.
* You can use `cordova (run|emulate) (ios|android|browser) -- --lr` now. lr means `live-reload`.
* Added `before_deploy` hook. You can check at: [beforedep.js](template_src/hooks/beforedep.js)
* [hookers.js](template_src/hooks/hookers.js) changed.
* [CordovaDeviceRouter.js](template_src/webpack/dev_helpers/CordovaDeviceRouter.js) added. In `live-reload` mode, server injects the `cordova.js` file according to where you are connecting.
* [device_router.html](template_src/webpack/dev_helpers/device_router.html) added. In `live-reload` mode, this file routes you to right location.
