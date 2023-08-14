#Customised for the Msc. Thesis of Jasper-Jan Lut

###Custom files:
- **src\cfclient\ui\tabs\FlightTab.py**: This is the modified flight tab. It supports the custom VLC link.

- **src\cfclient\ui\tabs\flightTab.ui**:
This is the modified flight tab. It supports the custom VLC link UI interface.

### Other repositories this work requires:
- MSC_Thesis_Jasper_Jan_Lut_2023_TuDelft: [link](https://github.com/GoLut/MSC_Thesis_Jasper_Jan_Lut_2023_TuDelft.git)
- The custom crazyflie firmware: [link](https://github.com/GoLut/crazyflie-firmware)


# Crazyflie PC client [![CI](https://github.com/bitcraze/crazyflie-clients-python/workflows/CI/badge.svg)](https://github.com/bitcraze/crazyflie-clients-python/actions?query=workflow%3ACI) [![cfclient](https://snapcraft.io//cfclient/badge.svg)](https://snapcraft.io/cfclient)


The Crazyflie PC client enables flashing and controlling the Crazyflie.
It implements the user interface and high-level control (for example gamepad handling).
The communication with Crazyflie and the implementation of the CRTP protocol to control the Crazyflie is handled by the [cflib](https://github.com/bitcraze/crazyflie-lib-python) project.

## Installation
See the [installation instructions](docs/installation/install.md) in the GitHub docs folder.

## Official Documentation

Check out the [Bitcraze crazyflie-client-python documentation](https://www.bitcraze.io/documentation/repository/crazyflie-clients-python/master/) on our website.

## Contribute
Go to the [contribute page](https://www.bitcraze.io/contribute/) on our website to learn more.

### Test code for contribution
Run the automated build locally to test your code

	python3 tools/build/build
