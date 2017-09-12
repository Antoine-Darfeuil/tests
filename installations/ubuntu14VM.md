

$ sudo apt-get update


## Python 2.7
` $ wget https://bootstrap.pypa.io/get-pip.py && sudo python get-pip.py  `   ***(lastest version of pip)***   
` $ sudo pip install numpy  `   
` $ sudo apt-get install python-matplotlib  `   

# Image Processing


## OpenCV :
**Step 3** Install OpenCV.   
MXNet uses OpenCV for efficient image loading and augmentation operations.   
` $ sudo apt-get install -y libopencv-dev ` 

*Sans doute requis pour mxnet, ca ne permet pas d'utiliser cv2 en python*   
**Build OpenCV from source :**
- Link : http://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html   
- Link2 : http://docs.opencv.org/3.0-beta/doc/tutorials/introduction/linux_install/linux_install.html   
` [compiler] sudo apt-get install build-essential  `   



# Machine learning frameworks

## Scikit-learn :
` $ sudo pip install scipy  `   
` $ sudo pip install -U scikit-learn  `   
` $ sudo apt-get install python-pandas  `   

# Deep learning frameworks

## Install MXNet (CPU) :
Install MXNet with OpenBLAS acceleration :   
` $ pip install mxnet  `   
` $ sudo apt-get install graphviz  ` ***(already install graphviz + install mxnet 0.10.0 post 2)***      
` $ pip install graphviz  `   

## Install Tensorflow  :

## Install Caffe :
