# CentOS Test Docker on ARM64 Mac

This project contains an example of how to install x86 VM with Docker on the Macbook Pro with M1 Pro CPU.

# Motivation

I've gathered many guides in one place and already tried many approaches (I've excluded) them already about how to get an x86 VM Machine in macOS with an M-series CPU.

# Dependencies

1. QEMU (tested with the version: 8.1.1)
2. Vagrant (tested with the version: 2.3.7)
3. Vagrant Qemu Plugin (tested with version: 0.3.5)
4. Vagrant Host Manager Plugin (tested with version: 1.8.10)
5. Mac OS (tested with the version 13.5.1 (22G90))
6. Vagrant CentOS box (name: generic/rhel7, version: 4.3.2)

# How to
If you already have all dependencies installed just run it with Vagrant:
`vagrant up`
