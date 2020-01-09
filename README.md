# FasterRCNNGPU
一个简单带注释的FasterRCNN实现

1. 代码实现基于 https://github.com/chenyuntc/simple-faster-rcnn-pytorch
2. 基本将所有的代码都写进同一个jupyter了，方便查找代码节
3. 用 Pytorch 0.4 实现
4. BUG：训练时内存会不断增大，直到爆内存，
    可能是python线程的Bug，也可能是Image包的Bug。
