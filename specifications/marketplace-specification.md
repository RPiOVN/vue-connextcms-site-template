**12/7/17 CT: This spec is out of date and no longer accurately reflects the UI**

# Marketplace Specification Overview
This document contains the specifications for the **Marketplace** software. The Marketplace software is defined by the following
high-level features:

* Owned Device Management
* Rented Device Management
* Marketplace
* Testing

The sections below detail the specifications for each of these features:

## Owned Device Management
![Owned Devices](images/owned-devices-mockup.JPG?raw=true "Owned Devices Mock Up")

A mockup of the owned devices view is displayed above.

## Rented Device Management
![Rented Devices](images/rental-mockup.JPG?raw=true "Rented Devices Mock Up")

A mockup of the rented devices view is displayed above.

## Marketplace
![Marketplace Mockup](images/marketplace-mockup.JPG?raw=true "Marketplace Mock Up")

A mockup of the Marketplace view is displayed above.


## Testing
Testing of server code will use the same test-suite provided by the
[vue-template/webpack repository](https://github.com/vuejs-templates/webpack), which this project was generated
from. Namely, Mocha will be used for unit tests and Karma will be used for end-to-end testing. We badly need
a contributor to help us setup and maintain a suite of testing scripts and set up Continuous Integration testing.
