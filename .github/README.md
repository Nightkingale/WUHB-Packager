# WUHB Packager

A Wii U homebrew packager for use with Aroma.

<p align="left">
  <a href="https://discord.nightkingale.com/">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join us!" width="10%" height="10%">
  </a>
  <a href="https://donate.nightkingale.com/">
    <img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="Thank you!" width="10%" height="10%">
  </a>
  <a href="https://nightkingale.com/">
    <img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="Visit us!" width="10%" height="10%">
  </a>
</p>

WUHB Packager is a graphical wrapper for wuhbtool, easing the process of packaging homebrew files for the Aroma environment.

## Installation
A Windows executable will be bundled with each release. Linux users will need to use the Python script in the source code in order to run the program.

* It is crucial to have wuhbtool installed correctly, which comes in [wut-tools](https://github.com/devkitPro/wut-tools). Without this installed, the program will refuse to package any homebrew. Please refer to that repository for installation instructions.

## Usage
In order to use the program, you'll need to at least have the homebrew you'd like to package in RPX format.

* Besides the executable, you can also provide a `/content` directory (if necessary), a name, pictures, and more. None of this is required, but it's encouraged for your homebrew to be more recognizable on the Wii U Menu. If anything is missing, the program will alert you, but any warnings can be dismissed.
* When a homebrew executable has been provided, a button will be available that allows you to package the homebrew. Clicking it will ask where to save the resulting WUHB file, and anything that should be brought to your attention will show here.

## Assistance
If you encounter bugs, the best place to report them would be the [Issues](https://github.com/Nightkingale/WUHB-Packager/issues) tab. This allows for easy tracking and reference, though please check for duplicates first and comment there if possible!

For assistance or other inquiries, the best place to reach out would be the [Nightkingale Studios](https://discord.nightkingale.com/) Discord server ([#chat-hangout](https://discord.com/channels/450846070025748480/1127657272315740260) is okay). I am active in many other Wii U homebrew Discord servers as well.

### Frequently Asked Questions

**1. WUHB Packager doesn't start up! Why would this be the case?**

Remember that this tool is solely a wrapper for wuhbtool, meaning that you must have it installed in order for WUHB Packager to work. WUHB Packager is not an alternative to wuhbtool, rather an "assistant" for it. Refer to the error message shown, as well as the Installation instructions. If you are certain wuhbtool is installed, feel free to open an issue!

## Credits
I hope that I am able to express my thanks as much as possible to those who made this repository possible.
* [GaryOderNichts](https://github.com/GaryOderNichts), for testing WUHB Packager and assisting me throughout development.