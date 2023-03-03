# Router-Config
the code connects to a Cisco IOS router using SSH and enters enable mode.
It then sends a set of configuration commands to the router to configure the IP address of a loopback interface.
Finally, the code prints the output of the configuration commands and disconnects from the router.
Note that the specific commands used to configure a router will depend on the vendor and model of the device, as well as the desired configuration.
The Netmiko library provides support for a wide range of network devices and vendors, so be sure to consult the documentation for the library and the specific device you are configuring to ensure that the appropriate commands are used.
