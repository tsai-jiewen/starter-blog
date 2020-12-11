---
title: "在jupyter notebook上安裝R"
author: ''
date: '2020-11-16'
slug: jupyter
tags: []
categories: []
---


# 在jupyter notebook上安裝R


{%hackmd @yukai/medium-theme %}

@tsai-jiewen 
@Tsai-J 
@OmMDOuSSSgi-NbCDSZTTMQ 

[TOC]

#### 在線使用R
[binder](https://github.com/binder-examples/r)
有rstudio、r + jupyter、rshiny等選擇。

[Jupyter+R](http://mybinder.org/v2/gh/binder-examples/r/master?filepath=index.ipynb)
[RStudio](http://mybinder.org/v2/gh/binder-examples/r/master?urlpath=rstudio)
[RShiny](http://mybinder.org/v2/gh/binder-examples/r/master?urlpath=shiny/bus-dashboard/)



#### windows:
簡單的方法：通過Anaconda安裝R核心
```
conda install -c r r-essentials
```

#### mac



參考：[打造 Jupyter Notebook 資料科學環境](https://medium.com/datainpoint/jupyter-kernels-3151a6408bab)





Jupyter notebook 在預設情況下無法檢視變數內容，因此會造成檢視錯誤的困難。

解決辦法 :
```
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
jupyter nbextension enable varInspector/main
jupyter notebook
```
 

參考：https://volderette.de/jupyter-notebook-variable-explorer/
