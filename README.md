# Preamble

This is a collection of utilities related to the VGM format. The intention is primarily to mockup a procedure for handling VGM files in a cross-platform manner, with the intention of eventually creating cross-platform versions of existing open-source VGM tools.

# Installation

1. Download the *.js files to a directory that's accessible by your intended webpage or other JavaScript-capable development environment.
2. Reference the files in your project.
3. Follow the usage instructions below!

# Usage

There are currently tools that cover various aspects of handling VGM files on Windows; functionality provided by such tools include trimming and file optimization, dumping a VGM's statistics to a plain text file, converting a VGM file to a MIDI sequence, etc. Once all is said and done, there will ideally be JavaScript versions of each of these, providing the online JavaScript equivalent of VGMTool.

Instructions for usage of each tool will be provided as tools are added.

# API

Todo!

# Disclaimer

The [VGM format](http://www.smspower.org/Development/VGMFormat) is a file format that allows storage and playback of music sequences written for various video game console audio chips. Such audio chips include the Yamaha YM2413, YM2151, and YM2612 FM synthesizers, as well as the Texas Instruments SN76489/SN76496 programmable sound generator (PSG). Playback of VGM files requires successful emulation of the audio chips involved, and this project seeks to port such emulation to JavaScript (at least to VGM v1.50 spec, which encompasses the PSG, YM2413, YM2612, and YM2151 chips).
