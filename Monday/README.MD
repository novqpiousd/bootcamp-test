# Day 1 / Monday

## Morning: Science, project management and Git

The goal of this morning is to discuss how to manage a project as a graduate student, focusing on an example of managing a coding project with Git.

To get started you need to install Git itself and some command line tools.

### Installation Instructions

We'll be using git from the command line and through the Atom text editor.

#### Git and command line tools

MacOS:
1. Open terminal
2. `xcode-select --install`

Windows 10:
1. Control Panel -> Turn Windows features on and off -> enable "Windows subsystem for Linux"
2. Reboot
3. Windows Store -> search “Ubuntu” -> Install
4. Set up Ubuntu
  1. Open the command line
  2. `sudo apt update`
  3. `sudo apt install build-essential`
5. Go to a location Windows can see: `cd /mnt/c` or replace `c` with the drive letter of your choice

Ubuntu: All the tools we need are part of build-essential. Follow instruction under step 4 above to install it.

Other operating systems: You're on your own. We will be using Git from the command line.

You should now be able to enter `git --version` and have it return something like "git version 2.17.1". The version won't matter for what we're doing today.

#### Atom

Get download here: https://atom.io/

## Afternoon: A sample project and Matlab basics

### Install Instructions

UCI provides Matlab to students for free. To download and install it, follow the instructions here: http://laptops.eng.uci.edu/software-installation/matlab
