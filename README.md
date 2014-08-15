# Kitchenplan Configuration

This is a Kitchenplan configuration repository. This repository contains all configuration to install and configure our OSX workstations.

Kitchenplan is a small tool to fully automate the installation and configuration of an OSX workstation (or server for that matter) using Chef. But while doing so manually is not a trivial undertaking, Kitchenplan has abstracted away all of the hard parts.

More information about Kitchenplan and on how to use it can be found in the [Kitchenplan README](http://kitchenplan.github.io/kitchenplan/).

## Quick Start

Simply run the following command(s):

```sh
$ sudo gem install kitchenplan
$ kitchenplan setup https://github.com/unionco/kitchenplan-config.git
$ kitchenplan provision
```
