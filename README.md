# Sync Android

A script to synchronize stuff to and from my Android phone.

Basically a small shell script around [adb-sync](https://github.com/google/adb-sync).

## Requirements
* adb
* adb-sync

## Installation
Make the script executable and add it to your PATH.
For example:
* `chmod u+x sync_android`
* mkdir "$HOME/bin"
* `ln -s "$PWD/sync_android" "$HOME/bin"`
* add this line to your .bashrc: `export PATH="${PATH}:$HOME/bin`
* reload your .bashrc: `source ~/.bashrc`

## Other useful commands
* Explore phone:             `adb shell`
* Put file on phone:         `adb push FILE DEST`
* Retrieve file from phone:  `adb pull FILE DEST`
