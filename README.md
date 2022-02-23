# PicoFusee : Run Fusee Gelee on RP2040

* Based on kalumajs `https://kaluma.io/`
* Setup Kalamu Cli 
* Install the latest uf2 image on the pi pico
* Initialize `npm init -y` & install dependencies with `node install --save` [dependencies from package.json]
* `kaluma ports` to get the port of the pi pico 
* `kaluma flash ./index.js --port [port-address of pico] --bundle --no-load`
* `screen [port-address of pico] 115200` to test with `.load` command in the REPL
