### 配置环境参数
```
export PATH=/usr/local/cuda-10.0/bin${PATH:+:${PATH}}
export LD_LIBRARY_PATH=/usr/local/cuda-10.0/lib64\
                         ${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
```

### 配置Java jer 
> sudo apt-get install openjdk-8-jre

### 运行Nsight
> nsight -vm /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java