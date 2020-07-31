# asdf-crc

![CI](https://github.com/sqtran/asdf-crc/workflows/CI/badge.svg?branch=master)


[Red Hat CodeReady Containers](https://github.com/code-ready/crc) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.  This work is based off of the [minishift](https://github.com/sqtran/asdf-minishift) plugin.

Note that this is only supported on `macOS`, `RHEL 7.5+`, `Centos 7.5+`, and `Fedora`.  It may work on `Ubuntu`, but additional packages may be required.  

View the [CodeReady Docs](https://code-ready.github.io/crc/) Github Pages for in-depth details.

## Install

```bash
asdf plugin add crc https://github.com/sqtran/asdf-crc.git
asdf install crc latest
```

## Use

Check the [asdf](https://github.com/asdf-vm/asdf) README for instructions on how to install and manage versions of CodeReady Containers.
