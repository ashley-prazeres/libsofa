<div align="right">
<a href="http://www.sofaconventions.org/">
	<img alt="sofaconventions.org" width="160px" src="https://raw.githubusercontent.com/hoene/libsofa/master/11960889.png"/>
</a>
</div

#

# [S]patially [O]riented [F]ormat for [A]coustics, C++ library.

Library for reading and writing the standartized .sofa file format (AES69-2015).

## Badges

<div align="center">
<a href="https://travis-ci.org/hoene/libsofa">
<img alt="Travis CI Status" src="https://travis-ci.org/hoene/libsofa.svg?branch=master"/>
</a>
<a href="https://scan.coverity.com/projects/hoene-libsofa">
<img alt="Coverity Scan Build Status" src="https://scan.coverity.com/projects/20300/badge.svg"/>
</a>
<a href="https://ci.appveyor.com/project/hoene/libsofa-s142k">
<img alt="AppVeyor Status" src="https://ci.appveyor.com/api/projects/status/mk86lx4ux2jn9tddpo/branch/master?svg=true"/>
</a>
</div>

## Compile


On Ubuntu, to install the required components, enter

> sudo apt install libnetcdf-c++4-dev libjson-c-dev doxygen graphviz

Then, clone the git repository and go to this directory.

Then, to compile enter following commands

> mkdir -p build && cd build

> cmake -DCMAKE_BUILD_TYPE=Debug ..

> make all doxyDoc test



