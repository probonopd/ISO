# Gershwin ISO

This repository automates the build of Gershwin Installation media.

<img width="1392" alt="Screenshot 2024-08-11 at 11 03 14 PM" src="https://github.com/user-attachments/assets/42eaa069-fa02-45eb-a22c-4a2fef40781f">

### Requirements

* Debain 12
* live-build
* qemu-user-static (for ARM64)

## Building the ISO

Follow these steps to install Applications on Debian:

1. Clone the repository with submodules:

```
git clone https://github.com/gershwin-os/iso.git
```

2. Build the components:
```
cd iso && sudo ./build.sh
```
