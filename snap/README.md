# Unofficial Snap Packaging for XML Toolkit from the GNOME Project
![Icon of XML Toolkit from the GNOME Project](gui/icon.png "Icon of XML Toolkit from the GNOME Project")

**This is the unofficial snap for XML Toolkit from the GNOME Project**, *"XML C parser and toolkit developed for the Gnome project (but usable outside of the Gnome platform)"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `libxml2` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/libxml2-snap.svg "Build Status of the `libxml2` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/libxml2-snap)

![Screenshot of the Snapped Application](screenshots/xmllint-version.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation
([Don't have the `snap` command installed?](https://snapcraft.io/docs/core/install))

    # Install Snap #
    sudo snap install libxml2
    
    # Connect the Snap to Optional Interfaces #
    ## `removable-media`: For accessing XML files in removable media storage devices ##
    sudo snap connect libxml2:removable-media

## Exposed Commands
* `libxml2.xmllint` as `xmllint`
* `libxml2.xmlcatalog` as `xmlcatalog`

## What is Working
* `libxml2.xmllint --help`
* `libxml2.xmlcatalog --help`
* `libxml2.xmllint --format`

## What is NOT Working...yet 
Nothing so far.

## What is NOT Tested...yet
Everything not mentioned in the "What is Working" section.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/libxml2-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>

