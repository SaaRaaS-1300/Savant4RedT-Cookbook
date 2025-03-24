# 背景介绍与环境配置

```bash
# 设置 pip 源/升级 pip
!pip config set global.index-url https://mirrors.aliyun.com/pypi/simple 
!pip config set install.trusted-host mirrors.aliyun.com
!pip install --upgrade pip

# 安装 ms-swift
!pip install jieba==0.42.1
!pip install 'ms-swift[all]==3.2.1' awscli==1.38.14
!pip install tf-keras==2.19.0
!pip install vllm==0.8.1

# 更新 trl
!pip install -e trl/.[dev]
```