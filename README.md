# darkmini

Dark theme for rEFInd

[rEFInd](http://www.rodsbooks.com/refind/) is a simplistic boot manager for UEFI
based systems. This is a clean, dark and minimal theme for it.

![screenshot](https://raw.githubusercontent.com/LightAir/darkmini/master/screenshot_001.png "screenshot")
![screenshot](https://raw.githubusercontent.com/LightAir/darkmini/master/screenshot_002.png "screenshot")


### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/darkmini/theme.conf` at the end of
    `refind.conf`.
