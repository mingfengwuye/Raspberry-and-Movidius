# Raspberry-and-Movidius

# Hardware
## RaspberryPi 3 Model B
## Movidius Neural Compute Stick

# OS
Download Raspbian from https://www.raspberrypi.org/downloads/ , My version is November 2017, release date is 2017-11-29

# NCSDK
Movidius ncsdk is [v1.10.00.03](https://codeload.github.com/movidius/ncsdk/tar.gz/v1.10.00.03)

# TensorFlow
TensorFlow version is v1.1.0 from [samjabrahams](https://github.com/samjabrahams/tensorflow-on-raspberry-pi/releases)

You may need to change "cp34" to "cp35" in the filename.
You should make a 'output' dir in ncsdk-1.10.00.03/examples/tensorflow/inception_v1 and ncsdk-1.10.00.03/examples/tensorflow/inception_v3.
or there will be an error "ValueError: Parent directory of output/inception-v1 doesn't exist, can't save."
