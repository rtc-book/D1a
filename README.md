# vm-vagrant

This repository contains all files and instructions necessary to create your own virtual machine for your development environment to accompany the book _Real-Time Computing for Mechanical Engineers_. The following should work on a host machine with Windows, macOS, and Linux.

## Installation

1. Install Virtualbox: https://www.virtualbox.org/wiki/Downloads
2. Install the Extension Pack (same page).
3. Install Vagrant: https://www.vagrantup.com/downloads
4. Clone, fork, or download this repository. If you do not have `git` installed on your host computer, simply download this repository by clicking the green **Code** button, then **Download ZIP**, and unzip. We assume you now have this repo in a directory `vm-vagrant`.
5. There are two ways to generate the virtual machine. 
	1. In a [terminal window](#terminals), `cd` into the directory `vm-vagrant` and simply:
```console
vagrant up
```
	2. On macOS, double-click `mac-installer.app`.
	3. TODO On Windows, double click `win-installer.bat`.

After several minutes (the download is large), this will create a new VM called rtcbook-dist that should be available in VirtualBox and boot right up. Note that everything should be set up (needs testing) through Part 3 of the CDT for myRIO instructions here:
http://courses.washington.edu/mengr477/resources/CDT_for_myRIO.pdf

After this initial setup, the virtual machine can be accessed directly through Virtual Box.

## Terminals

A terminal is an interactive command-line program in which a user enters text commands that are interpreted and executed by the operating system.

For a nice tutorial introduction to the terminal on Windows, macOS, and Linux, see [this article](https://tutorial.djangogirls.org/en/intro_to_command_line/). Only the most rudimentary usage is required here.

In Windows, the standard terminal program is `cmd.exe`. 

On macOS, the standard terminal program is `Terminal.app`.

In all major operating systems, the only standard command needed here is `cd`: change directory. You will use this to navigate to the directory `vm-vagrant`.