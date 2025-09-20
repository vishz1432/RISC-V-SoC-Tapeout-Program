# RISC-V-SoC-Tapeout-Program

## A documentaion for the Tapeout program
------------------------------------------------------------------------------------------------
## Tools Installation 

**All the instructions for installation of required tools can be found here:**

### System Requirements

- 6 GB RAM
- 50 GB HDD
- UBUNTU 20.04 or higher
- 4 vCPU

### Resizing the Ubuntu window to fit the Screen
```bash
$ sudo apt update
$ sudo apt install build-essential dkms linux-headers-$(uname -r)
$ cd /media/specta/VBox_GAs_7.1.8/
$ ./autorun.sh.
```

## Tool Check 

**yosys**

```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
$ git submodule update --init --recursive
$ make 
$ sudo make install

```
***The image for the Yosys Download***













