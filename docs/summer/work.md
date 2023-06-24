# 工作进展
## 第一周（6/17~6/24）
> 第一周开始的两天不知道要干嘛，之后和学长meeting后确定先进行理论学习，尤其是深度学习和卷积，同时想办法理解一些项目的源码。于是找了一些[课程](knowledge/deep_learning.md),然后第一个准备理解的项目就是Coil20 数据集的由[北村南](https://blog.csdn.net/ccaoshangfei/article/details/128185277?ops_request_misc=&request_id=&biz_id=102&utm_term=coil20%E6%95%B0%E6%8D%AE%E9%9B%86&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-3-128185277.nonecase&spm=1018.2226.3001.4187)提供的[源码](https://github.com/BeiCunNan/Image_Classfiation_Coil20)  

- 王晋文 看coil源码，了解训练过程（但还没看懂）

- 李文韬 [吴恩达 深度学习课程及练习](https://github.com/Wentao677/2022-Machine-Learning-Specialization) 看完监督学习部分

- 林子超 [PyTorch深度学习实践](https://www.bilibili.com/video/BV1Y7411d7Ys/?spm_id_from=333.337.search-card.all.click&vd_source=e2b96538b3c2da2818bba0c80e8491e2)   看完前四集

>6.24

王 coil源码看懂，了解训练过程 优化函数RELU,池化，各种NET

林 [PyTorch深度学习实践](https://www.bilibili.com/video/BV1Y7411d7Ys/?spm_id_from=333.337.search-card.all.click&vd_source=e2b96538b3c2da2818bba0c80e8491e2)   看完前九集
- 网络构成（张量）1.2.准备数据集，模型，3.写出来损失，优化函数0代码 4.训练（正向，反向转播，张量降维，调权重）eporch batch
- 多维特征怎么输入 （引入多个权重）
- 把数转换成0到1里的数
- 二分类，多分类（谁的概率大就选谁，错的话就有一个反馈，交叉熵）
- pytorch 很多算法，自动算梯度

李 
[梯度](https://www.bilibili.com/video/BV1sW411775X/?spm_id_from=333.337.search-card.all.click&vd_source=ca432610751bd2ecb826c8e3dd00f791) 最基本的神经网络的数学细节 [反向传播数学原理（链式法则）](https://www.bilibili.com/video/BV16x411V7Qg/?p=2&spm_id_from=333.880.my_history.page.click&vd_source=ca432610751bd2ecb826c8e3dd00f791)
TenseFlow安装 （类似于pytorch）