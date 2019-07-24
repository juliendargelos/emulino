# Emulino

This is a fork from [ghewgill/emulino](https://github.com/ghewgill/emulino) intended to be built on Mac OS.

Emulino is an emulator for the Arduino platform by Greg Hewgill.
The instructions in this readme are highly inspired by [this tutorial](https://wiki.ubuntu.com/Emulino) from Ubuntu wiki.

## Install

Download a prebuilt binary from [repository releases](https://github.com/juliendargelos/emulino/releases) or [build it from source](#build-from-source).

## Usage

```bash
emulino YOUR_PROGRAM.hex
```

## Build from source

Clone the repository:

```bash
git clone git@github.com/juliendargelos/emulino
```

Make sure you have [scons](https://scons.org) installed on your machine or install it with [brew](https://brew.sh):

```bash
brew install scons
```

Go to the project folder and build the binary:

```bash
scons
```

You will get the `emulino` binary.
