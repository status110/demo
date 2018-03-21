# MRV driver

This is the default driver for MRV switches. The driver package contains the manifest file
and a single test case. We encourage you to use the test case's structure (main procedures
and functional procedures) as a stub for implementing drivers for other devices.

The driver implements the Layer 1 Switch interface and requires the following resource
properties:
* ipAddress (optional, but either ipAddress or Hostname must be specified)
* Hostname (optional, but either ipAddress or Hostname must be specified)
* username
* password

