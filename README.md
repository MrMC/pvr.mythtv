[![Build Status](https://travis-ci.org/janbar/pvr.mythtv.svg?branch=Krypton)](https://travis-ci.org/janbar/pvr.mythtv)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/3115/badge.svg)](https://scan.coverity.com/projects/3115)

# MythTV PVR
MythTV PVR client addon for [MrMC] (http://mrmc.tv)

## Build instructions

### Linux

1. `git clone -b Jarvis https://github.com/mrmc/mrmc.git`
2. `git clone -b Jarvis https://github.com/mrmc/pvr.mythtv.git`
3. `cd pvr.mythtv && mkdir build && cd build`
4. `cmake -DADDONS_TO_BUILD=pvr.mythtv -DADDON_SRC_PREFIX=../.. -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=../../xbmc/addons -DPACKAGE_ZIP=1 ../../xbmc/project/cmake/addons`
5. `make`

##### Useful links

* [MrMC's PVR user support] (http://mrmc.tv)
* [MrMC's PVR development support] (http://mrmc.tv)
