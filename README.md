# WUHB Packager

A Wii U homebrew packager for use with Aroma.

WUHB Packager is a graphical alternative to using the command-line to package homebrew files for the Aroma environment. It still relies on wuhbtool in order to work properly, however it may provide a much simpler way to package homebrew for those who prefer not to use command-line tools.

## Installation
A Windows executable will be bundled with each release. Linux users will need to use the Python script in the source code in order to run the program.
* It is crucial to have wuhbtool installed correctly, which comes in [wut-tools](https://github.com/devkitPro/wut-tools). Without this installed, the program will refuse to package any homebrew. Please refer to that repository for installation instructions.

## Usage
In order to use the program, you'll need to at least have the homebrew you'd like to package in RPX format.
* Besides the executable, you can also provide a `/content` directory (if necessary), a name, pictures, and more. None of this is required, but it's encouraged for your homebrew to be more recognizable on the Wii U Menu. If anything is missing, the program will alert you, but any warnings can be dismissed.
* When a homebrew executable has been provided, a button will be available that allows you to package the homebrew. Clicking it will ask where to save the resulting WUHB file, and anything that should be brought to your attention will show here.

## Credits
I hope that I am able to express my thanks as much as possible to those who made this repository possible.
* [GaryOderNichts](https://github.com/GaryOderNichts), for testing WUHB Packager and assisting me throughout development.