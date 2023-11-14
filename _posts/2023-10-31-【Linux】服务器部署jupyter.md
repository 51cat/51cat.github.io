---
title: TITLE
categories: [Animal, Insect]
tags: [bee]     # TAG names should always be lowercase
---

### 安装jupyter

```shell
conda create -n cenv
conda activate cenv
conda install -c anaconda jupyter
```
### 安装pykernal
```shell
conda install ipykernel
ipython kernel install --user --name=<any_name_for_kernel>
```
### 安装R kernel
```shell
conda install -c r r-irkernel
# use R ↓
IRkernel::installspec(name="<any_name_for_kernel>",displayname="<any_name_for_kernel>")
```
### 生成配置文件
```shell
jupyter notebook --generate-config
```
### 运行
```shell
jupyter notebook
```
