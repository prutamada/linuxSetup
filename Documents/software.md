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

**icedtea-7-plugin:i386** - Java compatible browser plugin for the Firefox family. Works great with Juniper VPN and aging applications.

**chromium** - The Open-Source version of Google's Chrome browser. Great for JavaScript programming.

### Databases
**sqlplus** [[Download Link](http://www.oracle.com/technetwork/topics/linuxx86-64soft-092277.html)] - Not part of the repos due to licensing, the basic client sqlplus binaries must be downloaded, and both the environment variables *PATH* and *LD_LIBRARY_PATH* should be set.
