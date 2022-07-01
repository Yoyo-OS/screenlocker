# Screen locker

[![Build](https://github.com/Yoyo-OS/screenlocker/actions/workflows/build.yml/badge.svg)](https://github.com/Yoyo-OS/screenlocker/actions/workflows/build.yml)

## Third Party Code

kcheckpass

## Dependencies

### Debian/Ubuntu

```
sudo apt install libpam0g-dev libx11-dev -y
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.
