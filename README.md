<img src="https://avatars3.githubusercontent.com/u/1965106?s=200&v=4" align="right">

[![Build Status](https://travis-ci.com/NxtStudios/p3d-rest.svg?branch=master)](https://travis-ci.com/NxtStudios/p3d-rest)

Panda3d REST
============
p3d-rest provides a panda native solution to performing RESTful HTTP GET/POST requests using non-blocking io.

## Building Panda3D REST
To build the ``rest.pyd`` file on Windows run the following commands from the
project root and build the resulting Visual Studio solution file.
```
mkdir build
cd build
cmake ..
```

### Mac/Linux
To build the ``rest.pyd`` file on MacOS/Linux run the following commands from the project root

```
mkdir build
cd build
cmake ..
make
```

### Requirements

- The Panda3D SDK (get it <a href="http://www.panda3d.org/download.php?sdk">here</a>)
- CMake 2.6 or higher (get it <a href="https://cmake.org/download/">here</a>)
- windows only: The thirdparty folder installed in the Panda3D sdk folder (See <a href="https://www.panda3d.org/forums/viewtopic.php?f=9&t=18775">here</a>)
- Cython (get it <a href="https://cython.org/">here</a>)

## License
Panda3D Discord is licensed under the MIT license. See the provided LICENSE file for details.
