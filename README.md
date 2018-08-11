# A python driver for android devices: pydroid

A complete library for interacting with android emulators and/or devices

It simply do remote call to the local adb binary, so `AndroidSDK` must be fully
installed.

Could leverage the [python-adb](https://github.com/google/python-adb)
pure python implementation of the adb protocol.

As a first approximation, it will use system binary `adb` command.

# Contribution guide

```bash
git clone git@github.com:elijahbal/pydroid.git
echo PYTHONPATH=\${PYTHONPATH}:$(pwd)/pydroid/src >> ~/.zshrc
source ~/.zshrc
```
