


<p align="center">
  <img width="180" src="https://avatars.githubusercontent.com/u/124246008?s=400&u=a5bd256981854b0f0dbbbb3e9c23b301b97a7281&v=4">
</p>

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/5611a4ac8b194ede8ede620aa9011394)](https://www.codacy.com/gh/megadrive-crypto/megadrive-coin/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=megadrive-crypto/megadrive-coin&amp;utm_campaign=Badge_Grade)

# MegaDrive Coin source code


## Building Megadrive coin 

### On *nix

Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

* http://gcc.gnu.org/
* http://www.cmake.org/
* http://www.boost.org/
* Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

**Advanced options:**

* Parallel build: run `make -j<number of threads>` instead of `make`.
* Debug build: run `make build-debug`.
* Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
* Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

### On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

* http://www.microsoft.com/
* http://www.cmake.org/
* http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands: 
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```

### Actions - Artifact files (work in progress)
- [makefile.yml](https://github.com/megadrive-crypto/megadrive-coin/actions/makefile.yml)
- [build.yml](https://github.com/megadrive-crypto/megadrive-coin/actions/build.yml)



And then do Build.
Good luck!
