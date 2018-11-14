### 准备环境
* ubuntu18.04 
* gcc 7.3.0 

### 安装命令
```
sudo dpkg -i cuda-repo-<distro>_<version>_<architecture>.deb
sudo apt-key add /var/cuda-repo-<version>/7fa2af80.pub
sudo apt-get update
sudo apt-get install cuda
```