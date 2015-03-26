Python app to demonstrate using inputs and outputs on a Raspberry Pi
================================================================================

This is a sample application shows how to use simple inputs and outputs on a
Raspberry Pi.  There is a server side component that runs in Bluemix (Cloud Foundry) and
a Python client that runs on a Raspberry Pi.

The input is a simple button.  The output is a simple LED.  If you click on/off
in the web UI in Bluemix it will turn a LED on/off.  If you press the button
it will send a text message using Twilio to the phone number and message you
type in the web ui.



To Use
================================================================================

```
cf push myappname
```

Replace myapp name with the name of your app (ex. python-raspberry-pi)

or click the button below

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/IBM-Bluemix/python-hello-world-flask.git)



license
================================================================================

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<http://www.apache.org/licenses/LICENSE-2.0>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
