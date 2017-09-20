# BrightAuthor on GNU/Linux

These are some scripts I wrote to automate an installation of BrightAuthor via
WINE. Using this method, I am able to create presentations and publish them to
an SD card for use with the target hardware.

## Usage

1. Download and unzip the BrightAuthor setup package to the cloned directory
2. Install WINE and winetricks
- On Arch Linux: `sudo pacman -S wine-staging winetricks`
3. `./install; ./run`

- - -

Tested with:
- Arch Linux / BrightAuthor v4.6.0.36
