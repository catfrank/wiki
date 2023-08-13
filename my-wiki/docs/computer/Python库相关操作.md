# Python 库相关操作

## 镜像源

阿里镜像源：`pip install xxx -i http://mirrors.aliyun.com/pypi/simple --trusted-host mirrors.aliyun.com`

## virtualenv 库

[知乎教程：https://zhuanlan.zhihu.com/p/105105183](https://zhuanlan.zhihu.com/p/105105183)

安装 virtualenv 库：`pip install virtualenv`

常用命令：

- 进入虚拟环境 -> `workon 虚拟环境名`
    - 如果workon提示“找不到文件”，则需要配置系统变量

- 退出当前虚拟环境 -> `deactivate`

- 创建虚拟环境 -> `mkvirtualenv 虚拟环境名`

- 删除虚拟环境 -> `rmvirtualenv 虚拟环境名`