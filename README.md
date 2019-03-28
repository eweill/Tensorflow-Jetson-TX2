# Tensorflow-Jetson-TX2

This repository holds prebuilt .whl files for installing Tensorflow on a Jetson TX2.  Current builds include 1.4.1, 1.5.0, 1.6.0., and 1.8.0

All .whl files can be found under `Releases`.

Currently 1.4.1, 1.5.0, 1.6.0, 1.7.0, and 1.10.0 are built for Jetpack 3.1 (Python 2.7)

Currently 1.8.0 is built for Jetpack 3.2 (Python 2.7)

## Installing TF on Jetson TX2

To install Tensorflow on the Jetson, simply download the release that matches the needed version and `pip install` it as follows:

```
$ wget --no-check-certificate <link-to-whl-file>
$ sudo pip install <package-name>.whl
```

### ToDo List

- [x] Create Tensorflow wheels (.whl) for Python 2.7 (Jetpack 3.1)
- [ ] Create Tensorflow wheels (.whl) for Python 3.5 (Jetpack 3.1)
- [ ] Create Tensorflow wheels (.whl) for Python 2.7 (Jetpack 3.2)
- [ ] Create Tensorflow wheels (.whl) for Python 3.5 (Jetpack 3.2)
- [ ] Merge repo for creating wheels from compiling Tensorflow source

> NOTE: All wheel files were built from source using Bazel 0.10.1.  Other versions may work, but have note been tested.

This repository would like to acknowledge the following Github repositories:

- [jetsonhacks/installTensorFlowTX2](https://github.com/jetsonhacks/installTensorFlowTX2)
