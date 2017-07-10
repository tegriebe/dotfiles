# dotfiles

My dotfiles for configuring MacOS and RedHat based Linux distributions.
Support for debian based distributions may come later on.

The configuration of my most used tools is done using Ansible roles. 

## Tools installed and configured

* Dash (MacOS) and Zeal(Linux) respectively
* git and git-lfs
* zsh in addition with [prezto](https://github.com/sorin-ionescu/prezto)
 
## Prerequisites

Right now, you have to have the following tools installed:

* Ansible (>= 2.x)
* git

In the future it is planned to write a small shell script
that installs Ansible automatically depending on the OS
and distribution you are using. 
