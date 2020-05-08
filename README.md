# Dive-into-CV-PyTorch

《动手学CV-Pytorch版》

持续更新中...

## 开发阅读

使用markdown编写教程

为避免GitHub的网络问题，教程中使用的图片全部上传到项目的`markdown_imgs`目录下，并在md文件中使用类似`![test img](../../markdown_imgs/test_img.jpg)`的相对路径进行引用

在部分涉及比较多理论的章节，为了让公式正常显示，强烈建议安装chrome的`MathJax Plugin for Github`插件。

以下是目录与代码更新进度

## 动手学CV-Pytorch 入门篇

* 1\. 预备知识
    - [ ] 1.1深度学习简介
    - [ ] 1.2 环境配置
    - [ ] 1.3 数据操作
    - [ ] 1.4 自动求梯度
* 2\. 图片分类入门
    - [ ] 2.1 数据读取与数据扩增
        - [ ] 2.1.1 常见数据集介绍
        - [ ] 2.1.2 pytorch数据读取方法简介
        - [ ] 2.1.3 图像分类常见数据扩增方法
        - [ ] 2.1.4 读取数据并进行数据扩增示例
    - [ ] 2.2 图像分类介绍
        - [ ] 2.2.1 卷积神经网络基础
            - [ ] 二维卷积层
            - [ ] 填充和步幅
            - [ ] 多输入通道和多输出通道
            - [ ] 池化层
    - [ ] 2.3 经典图像分类模型介绍(根据情况删减)
        - [ ] 2.3.1 LeNet
        - [ ] 2.3.2 AlexNet
        - [ ] 2.3.3 VGG
        - [ ] 2.3.4 网络中的网络（NiN）
        - [ ] 2.3.5 含并行连结的网络（GoogLeNet）
        - [ ] 2.3.6 批量归一化（Batch Normalization）
        - [ ] 2.3.7 残差网络（ResNet）
    - [ ] 2.4 模型训练与验证
        - [ ] 2.4.1 模型训练与调参
        - [ ] 2.4.2 模型微调
        - [ ] 2.4.3 模型保存与加载
    - [ ] 2.5 模型集成
* 5\. 目标检测入门
    - [ ] 5.1 目标检测基础
        - [x] [5.1.1 目标检测与边界框](https://github.com/monkeyDemon/Learn_Dive-into-DL-PyTorch/tree/master/chapter09_object_detection/9.1_object_detection_basics/9.1.1_object_detection_and_bounding_boxes)
    - [ ] 5.2 目标检测数据集
        - [x] [5.2.1 皮卡丘数据集](https://github.com/monkeyDemon/Learn_Dive-into-DL-PyTorch/tree/master/chapter09_object_detection/9.2_object_detection_datasets/9.2.1_Pikachu_dataset)
        - [x] [5.2.2 VOC数据集](https://github.com/monkeyDemon/Learn_Dive-into-DL-PyTorch/tree/master/chapter09_object_detection/9.2_object_detection_datasets/9.2.2_PASCAL_VOC_dataset)
        - [ ] 5.2.3 COCO数据集
    * [5.3 目标检测和边界框](https://github.com/monkeyDemon/Learn_Dive-into-DL-PyTorch/blob/master/chapter09_computer_vision/9.3-9.5_object_detection_basics/9.3_object_detection_and_bounding_boxes.md)
    * [5.4 锚框](https://github.com/monkeyDemon/Learn_Dive-into-DL-PyTorch/blob/master/chapter09_computer_vision/9.3-9.5_object_detection_basics/9.4_anchor_boxes.md)
    - [ ] 9.5 多尺度目标检测
    - [ ] 9.7 单发多框检测（SSD）
    - [ ] 9.8 区域卷积神经网络（R-CNN）系列
    - [ ] 9.9 语义分割和数据集
    - [ ] 9.10 全卷积网络（FCN）
    - [ ] 9.11 样式迁移
    - [ ] 9.12 实战Kaggle比赛：图像分类（CIFAR-10）
    - [ ] 9.13 实战Kaggle比赛：狗的品种识别（ImageNet Dogs）


持续更新中......



## 引用

如果您在研究中使用了这个项目请引用原书:

```
@book{zhang2019dive,
    title={Dive into Deep Learning},
    author={Aston Zhang and Zachary C. Lipton and Mu Li and Alexander J. Smola},
    note={\url{http://www.d2l.ai}},
    year={2020}
}
```


