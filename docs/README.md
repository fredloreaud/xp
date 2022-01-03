# H1
Some text
## H2
### H3
#### H4
##### H5
###### H5

# [H1 link](https://se-deviceintelligence.github.io/se-dbus/)

Some text

# Table of contents

* [Classes](#classes)
* [Clone](#clone)
* Classes
* Clone

# Classes
![some link](se-dbus-classes.svg "SE Linux d-bus classes")

* SdBusEndpoint reserves sd-bus system connection for client & server
* SdBusClient provides introspection of any object and calls to any simple get/set methods
  * SdBusClient might be extended to call more complex methods and/or introspect a specific object by default
* SdBusServer handles object identification and processes its methods
  * SdBusServer might be extended to encapsulate identification setup and methods implementation

# Clone
````
git clone git@github.com:SE-DeviceIntelligence/se-dbus.git
````
