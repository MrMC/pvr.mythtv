[![Build Status](https://travis-ci.org/janbar/pvr.mythtv.svg?branch=Krypton)](https://travis-ci.org/janbar/pvr.mythtv)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/3115/badge.svg)](https://scan.coverity.com/projects/3115)

# MythTV PVR
MythTV PVR client addon for [MrMC] (http://mrmc.tv)

### Linux, BSD, OSX

Start by creating a build folder
<pre><code>mkdir -p build
rm -rf build/*
cd build/</code></pre>

To build PVR addon execute the following:
<pre><code>cmake -DCMAKE_BUILD_TYPE=Release -DPACKAGE_ZIP=ON ../
make</code></pre>

Finally generate the individual ZIP archive (which can then be installed manually): 
<pre><code>make package</code></pre>

##### Useful links

* [MrMC's PVR user support] (http://mrmc.tv)
* [MrMC's PVR development support] (http://mrmc.tv)
