# Performance Node

# RDK X3 & RDK X3 Module 性能检测应用，监测CPU, BPU, Memory和Disk

该应用基于Web网页打造，无论是什么品牌的电脑和手机，只需要在浏览器访问即可。

<img src=".\doc\desktop_demo.jpg" alt="desktop_demo" style="zoom:70%;" />

<img src=".\doc\mult_device.jpg" alt="mult_device" style="zoom:70%;" />

安装requirements，主要是Flask和pstiul

```bash
pip install -r requirements.txt -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com
```
```bash
# requirements
psutil==5.9.6
flask==3.0.0
```


运行

```
source /opt/tros/setup.bash
source ./install/local_setup.sh
ros2 run performance_node_pkg_py performance_node
```

在同一局域网访问X3的5000端口即可

```bash
192.168.xxx.xxx:5000
```



