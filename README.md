# Installing-SVP-4-Linux

This repository lists the installation instructions for [Smooth Video Project 4](https://www.svp-team.com/wiki/Download) on Linux Mint as of April 4, 2019

## Successfully installed on system:

OS: Linux Mint 19.1 Tessa

KERNEL: 4.15.0-46-generic

CPU: Intel Core i7-4771 @ 3.50GHz

GPU: NVIDIA GeForce GTX 1080 Ti

GPU DRIVER: NVIDIA 418.43

RAM: 32 GB

## Install Dependancies:

### mediainfo
```Bash
sudo apt-get install mediainfo
```

### mpv and Vapoursynth
```Bash
sudo add-apt-repository ppa:djcj/vapoursynth 
sudo apt-get update 
sudo apt-get install mpv
```

### SMPlayer
```Bash
sudo add-apt-repository ppa:rvm/smplayer 
sudo apt-get update 
sudo apt-get install smplayer smplayer-themes smplayer-skins
```

### Qt5.5
```Bash
sudo apt-get install qtdeclarative5-dev
```

## Installing SVP4

[Download the .run file](https://www.svp-team.com/wiki/Download) for SVP4 for Linux

Allow execution of the file as program

Run it
```Bash
./svp4-linux-64.run
```

Walk through the installation process.
