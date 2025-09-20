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
 **The image for the Yosys Download:**

<img width="1714" height="498" alt="Screenshot 2025-09-20 020834" src="https://github.com/user-attachments/assets/aaece520-380a-4f20-815f-a7bb6e88c20d" />


**Iverilog**

```bash
$ sudo apt-get update
$ sudo apt-get install iverilog

```

<img width="938" height="437" alt="Screenshot 2025-09-20 205708" src="https://github.com/user-attachments/assets/da7fc5fb-a11c-4fe4-8806-aa06e56b6c08" />


**gtkWave**

```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```

<img width="1280" height="520" alt="Screenshot 2025-09-20 022407" src="https://github.com/user-attachments/assets/60107e57-662b-4a7c-9605-b9e5bf66a47d" />




















