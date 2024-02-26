# Wick Editor

Wick is a browser-based hybrid animation/coding environment for making interactive things for the web, heavily inspired by similar tools such as Flash, HyperCard, and Scratch. It was developed in response to a growing need for such a tool for the modern web. Wick is currently live at [www.WickEditor.com](http://wickeditor.com/), come check it out sometime!

## How to run the editor locally for development
* Clone or download and unzip this repo
* Open terminal in the newly made `wick` folder and start an HTTP server:
  * `python -m SimpleHTTPServer` (Python 2)
  * `python -m http.server` (Python 3)
* OR if you have npm installed, you can get [http-server](https://github.com/indexzero/http-server), which is faster
  * `npm install http-server -g` to install
  * `http-server` to start
* Open a browser window, and go to `http://localhost:8000/`
