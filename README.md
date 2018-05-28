e3-amcpico8  
======
ESS Site-specific EPICS module : amcpico8

This module can install only header files into E3 for e3-pico8. 


## Install Header Files into E3

```sh
$ make install
```

## Build, Install, Clean Kernel Module and its releated configuration

```sh
$ make modules
$ make modules_install
$ make setup
```

```sh
$ make modules_clean
$ amke set_clean
```

Note that this is not valid for the cross-compiler. 