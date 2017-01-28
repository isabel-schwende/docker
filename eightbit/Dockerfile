# Adapted from official tensorflow binaries Dockerfile (version 15 Jan 2017): 
# https://github.com/tensorflow/tensorflow/blob/master/tensorflow/tools/docker/Dockerfile.devel
FROM tensorflow/tensorflow:latest-devel

MAINTAINER Isabel Schwende<isabelschwende@yahoo.d>

# Set up project repository and data
WORKDIR /root
RUN git clone https://github.com/isabel-schwende/TensorFlowCode.git && \
    cd TensorFlowCode && \
    curl -fSsL -O http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/bvlc_alexnet.npy && \
    curl -fSsL -O http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/caffe_classes.py && \
    curl -fSsL -O http://www.cs.toronto.edu/~guerzhoy/tf_alexnet/poodle.png

