# Raspberry-and-Movidius

# Hardware
## RaspberryPi 3 Model B
## Movidius Neural Compute Stick

# OS
Download Raspbian from https://www.raspberrypi.org/downloads/ , My version is November 2017, release date is 2017-11-29

# NCSDK
Movidius ncsdk is [v1.10.00.03](https://codeload.github.com/movidius/ncsdk/tar.gz/v1.10.00.03)

# TensorFlow
TensorFlow version is v1.1.0 from [samjabrahams](https://github-production-release-asset-2e65be.s3.amazonaws.com/53717060/cae971ae-2d9c-11e7-8c3e-f264b3c40935?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20171215%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20171215T014620Z&X-Amz-Expires=300&X-Amz-Signature=f57c61817d7b8f62f601e9ca786442f8d73d252e85641f1aef5fcbc28f41b955&X-Amz-SignedHeaders=host&actor_id=13177804&response-content-disposition=attachment%3B filename%3Dtensorflow-1.1.0-cp34-cp34m-linux_armv7l.whl&response-content-type=application%2Foctet-stream)
You may need to change "cp34" to "cp35" in the filename.
You should make a 'output' dir in ncsdk-1.10.00.03/examples/tensorflow/inception_v1 and ncsdk-1.10.00.03/examples/tensorflow/inception_v3.
or there will be an error "ValueError: Parent directory of output/inception-v1 doesn't exist, can't save."
