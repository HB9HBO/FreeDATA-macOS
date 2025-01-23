## FreeDATA Scripts for Mac OSX

### Preface
The installation requires an already working MacPorts installation, please follow the instrutions on https://www.macports.org/install.php.
The developer installation is not tested yet.


#### Short MacPorts install description
Install the Apple Developer Command Line Tools
Open the Terminal and execute the following command:
```
% xcode-select --install
```
Download the required MacPorts version from the link above and install it as usual.


### Install FreeDATA
Open the Terminal and execute the following commands:
```
% mkdir ~/freedata
% cd ~/freedata
% curl -o install-freedata-macos.sh https://github.com/HB9HBO/FreeDATA-macOS/blob/main/install-freedata-macos.sh
% curl -o run-freedata-macos.sh https://github.com/HB9HBO/FreeDATA-macOS/blob/main/run-freedata-macos.sh

% bash install-freedata-macos.sh
```

### Run FreeDATA
As usual, open the Terminal and execute the following commands:
```
$ cd ~/freedata
$ bash run-freedata-macos.sh
```
Your browser should open the FreeDATA webinterface. For configuring FreeDATA, follow the instructions unter https://wiki.freedata.app.



