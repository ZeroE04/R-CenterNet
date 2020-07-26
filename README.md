# R-CenterNet(中文)
基于CenterNet的旋转目标检测

### demo
* R-DLADCN(推荐)
    * ![image](ret/R-DLADCN.jpg)
* R-ResDCN(主干网用的ResNet而不是DLA)
    * ![image](ret/R-ResDCN.jpg)
* R-DLANet(如果你不会编译DCN，就使用这个没有编译DCN的主干网)
    * ![image](ret/R-DLANet.jpg)
* DLADCN.jpg
    * ![image](ret/DLADCN.jpg)

#### notes
 * 我对CenterNet[原版代码](https://github.com/xingyizhou/centernet) 进行了重构，使代码看起来更加简洁。
 * 如何编译DCN以及环境需求, 与[CenterNet](https://github.com/xingyizhou/centernet) 原版保持一致。
 * 关于数据处理与更多细节, 可以参考 [here](https://zhuanlan.zhihu.com/p/163696749)

### Related projects
* [CenterNet](https://github.com/xingyizhou/centernet)


# R-CenterNet(English)
detector for rotated-objections based on CenterNet/基于CenterNet的旋转目标检测

### demo
* R-DLADCN(this code)
    * ![image](ret/R-DLADCN.jpg)
* R-ResDCN(just replace cnn in resnet with dcn)
    * ![image](ret/R-ResDCN.jpg)
* R-DLANet(not use dcn if you don't know how to complie dcn)
    * ![image](ret/R-DLANet.jpg)
* DLADCN.jpg
    * ![image](ret/DLADCN.jpg)

#### notes
 * I refactored the original [code](https://github.com/xingyizhou/centernet) to make codes more concise.
 * How to complie dcn and configure the environment, refer to the original code of [CenterNet](https://github.com/xingyizhou/centernet).
 * For data processing and more details, refer to [here](https://zhuanlan.zhihu.com/p/163696749)

### Related projects
* [CenterNet](https://github.com/xingyizhou/centernet)
