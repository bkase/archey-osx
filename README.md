#Archey for OS X (the fast fork)
An archey script for OS X.
This fork runs FAST. ~50ms on my machine. I have removed information I don't personally need in order to speed up execution time.
For reference, `master` of the most up-to-date fork takes ~450ms on my machine.

```

                 ###
               ####
               ###
       #######    #######             User: bkase
     ######################           Hostname: kakariko
    #####################             Distro: OS X 10.11
    ####################              Kernel: Darwin
    ####################              Shell: /bin/zsh
    #####################             Terminal: xterm-256color iTerm.app
     ######################           CPU: Intel Core i7-3740QM CPU @ 2.70GHz
      ####################            Memory: 16 GB
        ################
         ####     #####

```

##Table Of Contents
* [Download](#download)
* [Installation](#installation)
* [Options](#options)
* [Credits](#credits)
* [License](#license)

##Download
The latest stable release is [1.4](https://github.com/obihann/archey-osx/archive/1.4.tar.gz).

##Installation
To get started you will need [homebrew](http://brew.sh/) to manage packages such as Python, figlet, and cowsay. To install please run the following command:

```
brew install archey
```

##Options
------------
* -b,  --nocolor : Use black & white logo
* -c,  --color   : Force using a color Logo
* -h,  --help : Show help


##Credits
------
* [djmelik](https://github.com/djmelik/archey) - Archey
* [joshfinnie](https://github.com/joshfinnie/archey-osx) - A great OSX Python port of Archey
* [Gary00](https://github.com/Gary00/archey-osx) - A fork of joshfinnie's Archey port, and the base of this script.
* [rdlugosz](https://github.com/rdlugosz) - Fixing a math error with memory caculations.
* [docwhat](https://github.com/docwhat) - Shell expertise and cleanups.
* [obihann](https://github.com/obihann) - Cleanup + current maintainer.

##License

This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Copyright [Jeffrey Hann](http://jeffreyhann.ca/) 2013,2014
