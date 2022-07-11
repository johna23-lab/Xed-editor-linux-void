# Xed Text Editor

Xed is a small and lightweight text editor., <b>now compiled for Linux Void x86_64</b>

<b>HOW TO INSTALL</b></br></br>
0-Download the xbps<br>
1-xbps-rindex -a xed-edit-3.2.4_1.x86_64.xbps<br>
2-sudo xbps-install -R $PWD xed-edit-3.2.4_1<br>

If you have some error messages runnig the editor try this<br>

<i>sudo glib-compile-schemas /usr/share/glib-2.0/schemas<br>
sudo /usr/bin/glib-compile-schemas /usr/local/share/glib-2.0/schemas/</i><br><br>


xed supports most standard editing features, plus several not found in your
average text editor (plugins being the most notable of these).

Although new features are always under development, currently xed has:

    * Complete support for UTF-8 text
    * Syntax highlighting
    * Support for editing remote files
    * Search and Replace
    * Printing and Print Previewing Support
    * File Revert
    * A complete preferences interface
    * Configurable Plugin system, with optional python support

Some of the plugins, packaged and installed with xed include, among others:

    * Change Case
    * Document Statistics
    * File Browser
    * Indent Lines
    * Insert Date/Time
    * Modelines
    * Save Without Trailing Spaces
    * Sort
    * Spell checker
    * Tag list
    * Word Completion


## Installation

```
    1. run the 'configure' script
      # meson --prefix=/usr build
    2. build xed
      # ninja -v -C build
    3. install xed
      # sudo ninja install -v -C build

    ** Build Instructions for Debian-based distros **
    1. run "dpkg-buildpackage" from the xed base directory
    2. cd ..
    3. run 
      # sudo dpkg -i *.deb
    4. From then, any new changes can be applied by running
      # sudo ninja -C debian/build install 
```

### Xed look and feel

##### Classic Mode
![classic-screenshot](https://github.com/linuxmint/xed/raw/master/screencaptures/classic_screencapture.png?raw=true)

##### Theme selections
![theme-screenshot](https://github.com/linuxmint/xed/raw/master/screencaptures/theme_screencapture.png?raw=true)

##### Search and Replace feature
![search-replace-screenshot](https://github.com/linuxmint/xed/raw/master/screencaptures/search_replace_screencapture.png?raw=true)

##### Select from several languages in Highlight syntax mode
![highlightmode-screenshot](https://github.com/linuxmint/xed/raw/master/screencaptures/highlightmode_screencapture.png?raw=true)

##### Xed Shortcuts
![shortcuts-1-screenshot](https://github.com/linuxmint/xed/raw/master/screencaptures/shortcuts_1_screencapture.png?raw=true)
![shortcuts-2-screenshot](https://github.com/linuxmint/xed/raw/master/screencaptures/shortcuts_2_screencapture.png?raw=true)



> xed is released under the GNU General Public License (GPL) version 2, see
> the file 'COPYING' for more information.
