osc-tools
=========

OSC (Open Sound Control) libraries and tools written in Java

osc-common 
-----------
Domain Model of OSC objects with Unit tests based on samples from the source site.

osc-network 
-----------
NETTY based client and server components.

osc-router 
-----------
(JavaFX based UI tool which allows you to route OSC messages from endpoint to endpoint [OSC to MIDI currently only supported].

This is a work in progress. It uses the java-fx-maven plugin from here https://github.com/zonski/javafx-maven-plugin/wiki

You will need to follow the instruction on the plugin page to ensure JavaFX is visible to the build.

![User interface](https://github.com/alistairrutherford/images/raw/master/oscrouterfx.png)

License
-------
Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
