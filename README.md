# My Bash Scripts

This repository contains a collection of handy Bash scripts for automating common tasks.


## Files Management
- **rmfspace**: Replaces spaces with underscores in all file names in the current directory.
- **rmdspace**: Replaces spaces with underscores in all directory names in the current directory.

## Android FTP Utilities
- **android-mount**: Mounts an FTP server running on an Android phone to access files.
- **android-umount**: Unmounts the Android FTP server.
- **getpic-android-ftp**: Transfers images from an Android phone to a local directory.

Setup Instructions


### Configuration file
Create a file `~/.credentials-android` with the following content:
```bash
USER="your_username"
PASS="your_password"
HOST="your_android_ip"
PORT="2221"
```

## Installation
Run the `install` script to install all scripts on your machine (single user install):
```bash
$ ./install
```

## Usage
Refer to the script names for their specific functionality.

