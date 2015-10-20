# mqtt-admin

MQTT Web Frontend: Publish, Subscribe and see Topic Status in a comfortable UI. 

## getting started

Download [the mqtt-admin.zip file](https://github.com/hobbyquaker/mqtt-admin/releases/latest), unzip, put it on a webserver and open index.html with a modern browser. You can also give it a try by just visiting https://hobbyquaker.github.io/mqtt-admin

I advice you not to connect to test.mosquitto.org. This server has too many retained topics, too big payload sizes, payloads with invalid utf and stuff like that - this will lead to very high load and memory usage of your browser.

#### mqtt-smarthome

mqtt-admin contains some syntactic sugar for [mqtt-smarthome](https://github.com/mqtt-smarthome/) users (special columns in status tab, auto-completion of // to /status/ and /set/)


## contributing

Pull Requests welcome!

Dependencies are managed with [Bower](http://bower.io/), [StealJS](http://stealjs.com/) takes care of module loading, 
the [Grunt](http://gruntjs.com/) task named "build" creates a production build in tmp dir.


## license

The MIT License (MIT)

Copyright (c) Sebastian Raff <hq@ccu.io> (https://github.com/hobbyquaker)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE. 
