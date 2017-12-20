# UDEV rules

This is my udev rules for embedded stuff on Ubuntu 17.04 which include:
  1. Openocd
  2. JLink
  3. Saleae Logic 4

## How to
```bash
$ sudo cp -r rules.d/*.rules /etc/udev/rules.d
$ sudo udevadm control --reload
```

## Questions
Please file an issue
