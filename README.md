## FreeDATA Scripts for Mac OSX

### Preface
The installation requires an already working MacPorts or Homebrew installation on your Mac, please follow the corresponding instrutions on https://www.macports.org/install.php or https://brew.sh 
The scripts run on Apple Silicon. I had it not tested on Intel Mac. 
I include two short instruction how to install MacPorts or Homebrew. Please install only one of them! 


#### Short MacPorts installation instructions
Install the Apple Command Line Tools
Open the Terminal, you find it in the Utilities Folder inside the Applications Folder, and execute the following command:
```
% xcode-select --install
```
Download the required MacPorts version from the link above and install it as usual. (Double click the pkg and follow the instructions) 


#### Short Homebrew installation instructions
Install the Apple Command Line Tools
Open the Terminal, you find it in the Utilities Folder inside the Applications Folder, and execute the following command:
```
% xcode-select --install
```
This will take some time, depending on the speed of your mac and internet connections. After successfull installation install brew:
```
% /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
brew tells you at the end of the installation, to execute some commands. please don't forget them. After that restart your computer.



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
Your browser should open the FreeDATA webinterface. For configuring FreeDATA, follow the instructions under https://wiki.freedata.app.



