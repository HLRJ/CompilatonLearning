# 安装  
https://tvm.apache.org/docs/  


`git clone --recursive https://github.com/apache/tvm tvm `    


`git submodule init`  


`git submodule update`  


sudo apt-get update    
sudo apt-get install -y python3 python3-dev python3-setuptools gcc libtinfo-dev zlib1g-dev build-essential cmake libedit-dev libxml2-dev 


sudo apt-get install -y llvm-10 llvm-10-dev llvm-10-tools clang-10 libclang-10-dev   

进入 tvm 文件夹  

mkdir build   
cp cmake/config.cmake build   

cd build   
cmake ..   
make -j4  

退到 tvm目录下  

conda env create --file conda/build-environment.yaml   

conda activate tvm-build   

降级  python3.8  

sudo  vi ~/.bashrc   

/path/to/tvm  是下载的tvm 目录   
export TVM_HOME=/path/to/tvm   
`export PYTHONPATH=$TVM_HOME/python:${PYTHONPATH}`   

pip3 install --user numpy decorator attrs   

pip3 install --user tornado  

pip3 install --user tornado psutil 'xgboost<1.6.0' cloudpickle  

检查是否安装好， 

python3  

import tvm  

`tvm.__version__  `

![如图](/course/MLCI%20TianqiChen/TVM/base/photos/checkVersion.png)