# Introduction
Package configuration file and Makefile to build OpenThread Border Router natively for Buildroot.
I was able to build and test otbr on a Beaglebone Black. Additional scripts are required for proper functionality. I referred to the otbr script directory when creating scripts for my board.

# Getting Started
- Copy these files to a new directory in the package directory present in your workspace.
- Source the configuration file in the package Config.in.
- Configure otbr in menuconfig.
- Build an image!
