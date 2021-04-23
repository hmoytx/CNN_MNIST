# 项目简介
之前入了机器学习的坑，无奈限于数学基本功，只能退而求其次学了tensorflow，因此写了一个基于tensorflow的利用CNN的MNIST手写数字识别的脚本，网上应该都有差不多类似的，毕竟很经典的例子，这里只是为了熟悉tensorflow重新写了一下。


  
# 运行环境
python3.6.4 windows10 (可选择anaconda)

## 第三方库
* 命令下载
```
pip install tensorflow
```
* anaconda可以直接在面板里下载

# 使用说明
* 直接运行CNN.py,会随着时间反馈训练的情况,训练准确率，测试准确率等。最后会在logs中有两个可视化的结果，需要用tensorboard打开。

# 注意
运行训练情况因电脑而异，未采用加速，对核心不是很好的电脑可能会导致死机现象。

