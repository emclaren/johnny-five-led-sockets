<h2>Project</h2>

This is a very small project for demo purposes using sockets and johnny five. Turns on an LED on pin 13 of arduino running standard firmata. 

Full set up instructions can be found here: https://www.hackster.io/geradrum/johnny-five-and-socket-io-led-web-switch-fb85cf




<h2>Install</h2>

```bash
# Using npm
npm install
```
```
# Using yarn
yarn install
```

<h2>Scripts</h2>

Starts a local server for this project.
```
npm run dev
```


*Note: I had trouble running the serialport package using npm install. Running this code found at  https://serialport.io/docs/guide-installation solved the issue:* 

`sudo npm install serialport --unsafe-perm --build-from-source
`

`npm rebuild serialport --build-from-source
`



Build the project to the /dist folder (html/css/js).

```
npm run build
```

Starts a local server for this project and runs the arduino.js file (localhost:4000)

```
npm run arduino:dev
```

Runs the arduino.js file without starting a local server, instead, the script connects to the production server (in this case, https://damp-stream-42889.herokuapp.com/ )

```
npm run arduino
```

<h2>LICENSE</h2>

Copyright 2017 geradrum

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
