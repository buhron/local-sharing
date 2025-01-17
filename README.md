# What is local-sharing?
local-sharing is a front-end for making a HTTP server, though its main purpose is to make sharing files easier, and faster.
## Choose your Edition
local-sharing will have two edition, the GTK edition which is compatible with only Linux (macOS with gtk-mac-integration), and the TK edition using tkinter which is compatible with all other platforms and Linux, it however has a UI from 2005.
## Installation
Installation should be possible by cloning this repo and running the following command:
```sh
# make install
```
Note that this will install local-sharing to `/usr/local`. Specify the ```$LS_PATH``` when running `make install`.
## Run from Source
Running from source should be possible by running this command:
```sh
LS_LAUNCH_TYPE=live python3 data/bin/local-sharing
```
