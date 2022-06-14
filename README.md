# ViTorch

## Quick Start Examples

Python >= 3.6.0 required with all [requirements.txt](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) dependencies installed:

```shell
$ git clone https://github.com/software-homework-team/ViTorch.git
$ cd ViTorch/code
$ pip install -r requirements.txt
```

run the code with

```shell
$ sh run.sh
```

## 本项目主要内容为神经网络可视化以及网络搭建。使用者可以无需代码经验，仅仅通过手动添加构建网络模型。面向广大深度学习爱好者，欢迎各位批评指正。
### 1.0版本卷积神经网络以及循环神经网络，2.0版本更新了注意力机制。


运行成功后将弹出ViTorch欢迎界面窗口,窗口上边从左到右分别是菜单按钮,各类网络层,和数据集按钮.![主界面](README.assets/%E4%B8%BB%E7%95%8C%E9%9D%A2.png)

点击菜单按钮,左侧弹出界面选择拦,有Desinger和Train两个选项.

![主界面2](README.assets/%E4%B8%BB%E7%95%8C%E9%9D%A22.png)

选择左侧的designer, 在上面可以选择神经网络层(如:激活函数,卷积,全连接等)来编辑神经网络

![编辑界面](README.assets/%E7%BC%96%E8%BE%91%E7%95%8C%E9%9D%A2.png)

编辑完成后可以点击编辑窗口下的generate按键,从而生成对应的pytorch神经网络模型对象

![编辑界面2](README.assets/%E7%BC%96%E8%BE%91%E7%95%8C%E9%9D%A22.png)

同时,还可以选择需要使用的数据集,在数据集选择的界面,可以预览到数据集的图像和一些基本信息,可以进行选择并下载

![数据集1](README.assets/%E6%95%B0%E6%8D%AE%E9%9B%861.png)

甚至也可以使用该软件diy需要的数据集![数据集2](README.assets/%E6%95%B0%E6%8D%AE%E9%9B%862.png)

这编辑完神经网络和选择了数据集之后,就可以开始训练神经网络模型了,可以在左侧的界面选择栏选择train,并且设置各种训练参数,接着就能开始训练了.

![训练界面](README.assets/%E8%AE%AD%E7%BB%83%E7%95%8C%E9%9D%A2.png)

在训练和过程中还可以实时显示训练曲线,动态观察神经网络的训练效果.

![训练界面3](README.assets/%E8%AE%AD%E7%BB%83%E7%95%8C%E9%9D%A23-1625589116125.png)



## document when designing

[可行性分析报告](document\可行性分析.md)

[软件设计说明书](document\软件设计.md)

[软件测试说明书](document\软件测试.md)

[需求分析报告](./document/需求分析.md)
