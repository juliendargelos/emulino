# Emulino

This is a fork from [ghewgill/emulino](https://github.com/ghewgill/emulino) intended to be built on **Mac OS**.

Emulino is an emulator for the Arduino platform by Greg Hewgill.

## Install

Download the [latest release](https://github.com/juliendargelos/emulino/releases/latest) or [build it from source](#build-from-source).

## Usage

```bash
emulino YOUR_PROGRAM.hex
```

## Build from source

Clone the repository:

```bash
git clone git@github.com:juliendargelos/emulino
```

Make sure you have [scons](https://scons.org) installed on your machine or install it with [brew](https://brew.sh):

```bash
brew install scons
```

Go to the project folder and build the binary:

```bash
scons
```

You will get the `emulino` executable.
