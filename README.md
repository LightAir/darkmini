# darkmini

Dark theme for rEFInd

[rEFInd](http://www.rodsbooks.com/refind/) is a simplistic boot manager for UEFI
based systems. This is a clean, dark and minimal theme for it.

## theme-mini
![screenshot](screenshots/screenshot_001.png "screenshot")
![screenshot](screenshots/screenshot_002.png "screenshot")
![screenshot](screenshots/screenshot_003.png "screenshot")
![screenshot](screenshots/screenshot_004.png "screenshot")
![screenshot](screenshots/screenshot_005.png "screenshot")

# theme

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/darkmini/theme-mini.conf` at the end of refind.conf
    Or add `include themes/darkmini/theme-mini.conf`
    And set option `banner` in theme file for select background image
    Ex: `banner themes/darkmini/bg/ubuntu_style.png  `
