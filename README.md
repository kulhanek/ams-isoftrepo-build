# ams-isoftrepo-build
Utilities for testing and building of the [ams-isoftrepo](https://github.com/kulhanek/ams-isoftrepo) package.

## AMS Servers Features:
* module descriptions

## Building and Installation

### Testing Mode
```bash
$ git clone --recursive https://github.com/kulhanek/ams-isoftrepo-build.git
$ cd ams-isoftrepo-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./04.build-inline.sh      # build the code inline in src/
```

### Production Build
```bash
$ git clone --recursive https://github.com/kulhanek/ams-isoftrepo-build.git
$ cd ams-isoftrepo-build
$ ./build-utils/00.init-links.sh
$ ./01.pull-code.sh
$ ./10.build-final.sh       # install dir: /opt/ams-isoftrepo/9.0
```




