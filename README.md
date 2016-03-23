# MasterPassword-Gtk
A Gtk (more specifically gtkmm) GUI implementation of the MasterPassword algorithm.

Parts of the code (more specifically /src/mpw-algorithm/) are taken from the original MasterPassword Github repository (https://github.com/Lyndir/MasterPassword). Some minor changes were made to provide compatibility to the rest of the code.

## Project State
Current version: 1.1

Note, that the master branch is now used as a kind of "stable" branch. Development takes place in a separate branch called dev.  

## Release Notes

### v1.0
First version. Basic functionality.

### v1.1
* Improved error handling
* Manage Accounts window

## Build
CMake is required to build this project.

The following libraries are required:
* libscrypt (https://github.com/technion/libscrypt)
* libcrypto (https://www.openssl.org/docs/manmaster/crypto/crypto.html)
* libconfig (http://www.hyperrealm.com/libconfig/)
* gtkmm (http://www.gtkmm.org/)
