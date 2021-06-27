# [brightnessctl_status](https://github.com/MEG4-hk/brightnessctl_status)

A simple and easy-to-use wrapper-tool above `brightnessctl` package.

- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Examples](#examples)

## Installation

Clone into the repo and copy the `brightnessctl_satatus` script where ever your scripts folder is. It's that easy.

```sh
$ git clone https://github.com/MEG4-hk/brightnessctl_status
$ cd brightnessctl_status
$ cp brightnessctl_status /path/to/script/folder
```

## Usage

I am all about simplicity, if possible. As a user, I only need 3 things regarding screen-brightness management tools:

- [increase](#increasing%20brightness) the brightness
- [decrease](#decreasing%20brightness) the brightness
- [get](#getting%20brightness) the current brightness

Thus, the tool has 3 simple options.

### Increasing brightness

* -i [VALUE]
 
 The -i option recieves how much (using precentage) to increase the brightness of the screen.

### Decreasing brightness

* -d [VALUE]
 
 Similar to -i, the -d option recieves how much (using percentage) to decreast the brightness of the screen.

### Getting brightness

* -g [OPTIONAL]
 
 Using the -g option will return the current brightness of your screen.

## Dependencies

- brightnessctl (obviously)

## Examples

```sh
$ brightnessctl_status -i 30
$ brightnessctl_status -g
```

The first example will increase the screens' brightness by 30%. The second will return the current brightness of the screen
