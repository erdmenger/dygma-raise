# Dygma Raise Keyboard Configurations

This repository contains configuration files for my [Dygma Raise](https://dygma.com/) programmable split keyboard.
The [Raise](https://dygma.com/) is not my first mechanical keyboard, but my first programmable keyboard and my first split keyboard. It can be configured using the [Bazecor](https://dygma.com/pages/bazecor) software. Most of the artifacts e.g. JSON files are exports from that software and should be importable again.

- [layers](layers/) contains the latest configuration file for my configured layers.
- [macros](marcos/) contains macro definitions used which need to be exported separately.

## Starting the BAZECOR Configuration Software
The [Bazecor](https://dygma.com/pages/bazecor) is not part of this repository itself. You can download it from the [Dygma web site](https://dygma.com/pages/bazecor) or check out the latest [Bazecor on GitHub](https://github.com/Dygmalab/Bazecor).
Make sure your Raise is connected via USB before you start Bacecor.

### Mac and Windows
On Windows and Mac all you need to do is to double click the [Bazecor](https://dygma.com/pages/bazecor) after you downloaded it.

### Linux
On Linux you might need to check the permissions of your user on the device file. You need to have READ-/WRITE- permissions on that device of course to load configurations from or safe them to your keyboard. On my Linux systems only `root` has read-/write permission such devices so I need to elevate access to all users `sudo chown o+RW /dev/ttyACM0` or grant access to my user `sudo chown $USER /dev/ttyACM0` where `/dev/ttyACM0` is the device file assigned by my Linux system to the keyboard after I plugged it in.
To ease my life I created a little shell script to do that for me before start Bazecor. Also I named the shell script `dygma.sh` so I don't have to remember that other name (Bazecor).

# Dygma and the Community
At the time I'm starting this Journey the main entry point into the world of the awesome DYGMA Raise programmable keyboard is the [Dygma Company Website](https://dygma.com).

Most of the community communication seems to happen on the [Dygma Lab Reddit community](https://www.reddit.com/r/DygmaLab/).

Happy hacking.