# 编程软件环境问题

## python pip 更换国内镜像源

### 国内镜像源

- 清华 <https://pypi.tuna.tsinghua.edu.cn/simple>
- 豆瓣 <http://pypi.douban.com/simple>
- 阿里 <http://mirrors.aliyun.com/pypi/simple/>
- 中科大 <https://pypi.mirrors.ustc.edu.cn/simple/>
- 华中理工 <http://pypi.hustunique.com/>
- 山东理工 <http://pypi.sdutlinux.org/>

### 临时使用

在使用pip时加参数 ```"-i https//pypi.tuna.tsinghua.edu.cn/simple"```

例如，从清华源镜像安装pyspider库

``` javascript
pip install pyspider -i https://pypi.tuna.tsinghua.edu.cn/simple
```

### 永久更改

- Linux 修改 ~/.pip/pip.conf(没有此文件夹及文件，创建)，内容如下：

``` javascript
[global]
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
[install]
trusted-host = mirrors.aliyun.com
```

- Windows 在user目录中创建pip目录，再新建pip.ini文件。如：```C:\User\ZhangSan\pip\pip.ini``` 内容同上。
