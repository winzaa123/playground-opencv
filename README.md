apt-get update
apt-get install libboost-all-dev
apt-get install aptitude
aptitude search boost

# tensorflow

python -m pip install -U matplotlib
pip3 install pillow
pip install scipy

pip install opencv-python
apt-get install libsm6 libxrender1 libfontconfig1

apt-get install libxext6

apt-get install python-pip python-dev python-virtualenv
virtualenv --system-site-packages ~/tensorflow
source ~/tensorflow/bin/activate

# object detection

https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md
<!-- apt-get install protobuf-compiler python-pil python-lxml
pip install jupyter
pip install matplotlib
wget https://github.com/google/protobuf/releases/download/v3.3.0/protoc-3.3.0-linux-x86_64.zip -->

cp -r pycocotools ~/tensorflow/models/research/

# Image

- [Jupyter]( https://towardsdatascience.com/tensorflow-object-detection-with-docker-from-scratch-5e015b639b0b)
- [Tensorflow Deploy](https://medium.com/@pierrepaci/deploy-tensorflow-object-detection-model-in-less-than-5-minutes-604e6bb0bb04)

# Image Realtime

- [Real-time image Github](https://github.com/datitran/object_detector_app)
- https://github.com/SethHWeidman/docker-object-detection
- https://github.com/aiformankind/object-detection

object detection Required !!
apt-get install -y git curl unzip
ENV DEBIAN_FRONTEND noninteractive 