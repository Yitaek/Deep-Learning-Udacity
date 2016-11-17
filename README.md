conda install virtualenv
conda create --name=tensorflow python-2.7

conda info -e
source activate tensorflow
pip install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.6.0-cp27-none-linux_x86_64.whl