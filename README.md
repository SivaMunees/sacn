# Horus

Horus is a general solution for 3D scanning. It provides graphic user interfaces for connection, configuration, control, calibration and scanning. It is ready to use with Open Source [Ciclop 3D Scanner](https://github.com/bq/ciclop).

This project has been developed in [Python](https://www.python.org/) language and it is distributed under [GPL v2](https://www.gnu.org/licenses/gpl-2.0.html) license.

More interest links are shown below:

* [Presentation](http://diwo.bq.com/en/presentacion-ciclop-horus/) [[es](http://diwo.bq.com/presentacion-ciclop-horus/)]
* [3D Design](http://diwo.bq.com/en/ciclop-released/) [[es](http://diwo.bq.com/ciclop-released/)]
* [Electronics](http://diwo.bq.com/en/zum-scan-released/) [[es](http://diwo.bq.com/zum-scan-released/)]
* [Firmware](http://diwo.bq.com/en/horus-fw-released/) [[es](http://diwo.bq.com/horus-fw-released/)]
* [Software](http://diwo.bq.com/en/horus-released/) [[es](http://diwo.bq.com/horus-released/)]
* [Documentation](http://diwo.bq.com/en/documentation-ciclop-and-horus/) [[es](http://diwo.bq.com/documentation-ciclop-and-horus/)]


## Installation

#### Supported versions

| Logo              | Name     | Versions     | Instructions                        |
|:-----------------:|:--------:|:------------:|:-----------------------------------:|
| ![][ubuntu-logo]  | Ubuntu   | 14.04, 14.10 | [link](doc/installation/ubuntu.md)  |
| ![][windows-logo] | Windows  | 7, 8, 8.1    | [link](doc/installation/windows.md) |
| ![][macosx-logo]  | Mac OS X | 10.9, 10.10  | [link](doc/installation/macosx.md)  |

#### Experimental versions

| Logo               | Name      | Versions | Instructions                         |
|:------------------:|:---------:|:--------:|:------------------------------------:|
| ![][debian-logo]   | Debian    | 8        | [link](doc/installation/debian.md)   |
| ![][raspbian-logo] | Raspbian  | RPi2     | [link](doc/installation/raspbian.md) |


## Development

Horus is an Open Source Project. Anyone has the freedom to use, modify, share and distribute this software. If you want to:
* run the source code
* make your own modifications
* contribute to the project
* build packages

follow the next instructions

#### GNU/Linux

Horus has been developed using [Ubuntu Gnome](http://ubuntugnome.org/), that is based on [Debian](https://www.debian.org/), like [Raspbian](https://www.raspbian.org/), [Mint](http://linuxmint.com/), etc. All instructions provided in this section probably work for most of these systems.

* [Ubuntu development](doc/development/ubuntu.md)

NOTE: *deb* and *exe* packages can be generated in *debian like* systems

#### Mac OS X

* [Darwin development](doc/development/darwin.md)

NOTE: *dmg* packages only can be generated in Mac OS X


[ubuntu-logo]: doc/images/ubuntu.png
[windows-logo]: doc/images/windows.png
[macosx-logo]: doc/images/macosx.png
[debian-logo]: doc/images/debian.png
[raspbian-logo]: doc/images/raspbian.png