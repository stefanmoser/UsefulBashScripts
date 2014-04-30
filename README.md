#Useful Bash Scripts
This repository contains a collection of bash scripts that I have found useful over the years.

## ¡WARNING!
Many of these scripts are based on conventions that I use and some of them do destructive things!  YMMV and use at your own risk!

## Usage
All usage is based on MINGW32.

In order to make these scripts available from any folder, you need to add the folder containing the scripts to the `PATH` variable.  I do it like this:

```
cd ~
touch .bashrc
notepad .bashrc
```

Add the following line:

```
export PATH=$PATH:/c/code/UsefulBashScripts
```