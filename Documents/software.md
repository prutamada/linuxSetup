### Package Management
To install packages from 32-bit repositories, enable the i386 architecture:

    sudo dpkg --add-architecture i386
    sudo apt-get update

The *apt-file* package is great for finding missing requirements:

    sudo apt-get install apt-file
    apt-file update
    apt-file search asound.so.2

### Web Browsers
**iceweasel:i386** - With a lot of enterprise applications still looking for 32-bit libraries (see *icedtea*), the i386 version of Iceweasel is recommended.
