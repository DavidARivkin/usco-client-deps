vendor depencies centralized, for usco project (browser)

General information
-------------------
This repository contains both the:


How to generate browser/polymer.js output ,with 'require' support:
------------------------------------------------------------------
Type: 

browserify -r url -r path -r minilog -r q -r composite-detect -r jszip > lib/usco-client-deps.js
