# 使用教程
原教程太繁琐了，tensorflow1.9之后已经支持树莓派(参考[TensorFlow 1.9 Officially Supports the Raspberry Pi](https://medium.com/tensorflow/tensorflow-1-9-officially-supports-the-raspberry-pi-b91669b0aa0))

此外，Protobuf也不必自己编译。

在此记录我的操作过程。

系统版本是Stretch。

### 安装 TensorFlow
```
sudo apt install libatlas-base-dev
pip3 install tensorflow
```

### 安装 Protobuf
`sudo apt-get install protobuf-compiler`

### 安装 OpenCV
`pip3 install opencv-python —user`

### 接下来
从步骤5之后和[原文档](https://github.com/wwj718/TensorFlow-Object-Detection-on-the-Raspberry-Pi#5-set-up-tensorflow-directory-structure-and-pythonpath-variable)一样。

这将省下你大量时间。
