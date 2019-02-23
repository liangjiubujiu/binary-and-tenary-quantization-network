# binary-and-tenary-quantizationnetwork-
将经典的[binary](https://github.com/MatthieuCourbariaux/BinaryNet) 和 [tenary](https://github.com/XJTUWYD/TWN) 网络使用 **`Python3`** 改写。使用jupyter notebook 进行可视化，保留了训练过程，详见[网盘链接](https://pan.baidu.com/s/14DJFtvLTwmRS3PTHsU3xEw ) 提取码：9so4 。
[report文件](https://github.com/liangjiubujiu/binary-and-tenary-quantizationnetwork-/blob/master/report.pdf)中整理了模型`所有测试的结果`。

## 实验一：binary network
### minist全连接分类网络
[mnist网盘](https://pan.baidu.com/s/1rNPE6ply0QUoJ-fZHnk-mw)或者[mnist.ipynb](https://github.com/liangjiubujiu/binary-and-tenary-quantizationnetwork-/blob/master/mnist.ipynb)文件中测试了一下三种网络结构下，使用-1,1 二值量化的神经网络识别准确率，约98.5%，结果如下。

<img src="https://github.com/liangjiubujiu/binary-and-tenary-quantizationnetwork-/blob/master/images/11.jpg" height="130" width="400" />

### cifar-10卷积分类网络
[cifar10网盘](https://pan.baidu.com/s/1A8GM__PZZ_5raPCBEiW3bg)或者[cifar10.ipynb](https://github.com/liangjiubujiu/binary-and-tenary-quantizationnetwork-/blob/master/cifar10.ipynb)文件中测试了一下三种网络结构下，使用-1,1 二值量化的神经网络识别准确率，约83.5%，结果如下。

<img src="https://github.com/liangjiubujiu/binary-and-tenary-quantizationnetwork-/blob/master/images/22.jpg" height="130" width="400" />


## 实验二：tenary weight network
### cifar-10卷积分类网络
[cifar10网盘](https://pan.baidu.com/s/1hWMNcGXy9MJx3EceNaR3rQ)或者[Untitled.ipynb](https://github.com/liangjiubujiu/binary-and-tenary-quantizationnetwork-/blob/master/Untitled.ipynb) 使用-1,1 和0三值量化的神经网络识别准确率为85.5%
