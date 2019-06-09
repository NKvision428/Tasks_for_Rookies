# Tasks_for_Rookies

欢迎来到[计算机视觉实验室](http://cv.nankai.edu.cn/)新手村。新手任务共分为以下几个部分：

>机器学习与深度学习基础

>文献搜集与特定领域发展情况总结

>深度学习编程框架学习与算法实现

>论文写作与rebuttal流程

>中英文邮件相关


## 1. 机器学习与深度学习基础

+ [机器学习（西瓜书，周志华著）](https://www.zhihu.com/question/39945249)；

***任务***：细读第二到第十四章，并任选一章整理分析。

+ [深度学习（花书，Goodfellow，Bengio等著）](https://github.com/zsdonghao/deep-learning-book/blob/master/dlbook_cn_public.pdf)；

***任务***：从第五章以后精读（尤其是7、8、9、11、12），理解并归纳机器学习中的正则化方法、优化方法以及卷积等操作。英语基础好的同学最好看英文版，以熟悉相关术语。

+ [斯坦福CS231n CNN for Visual Recognition](https://www.bilibili.com/video/av53754154?from=search&seid=6020411155113851809)，总时长约20小时；

***任务***：完成至少三次课堂作业，同时锻炼英语能力。


## 2. 文献搜集与特定领域发展情况总结

在Idea形成之前，应首先确定一个**大方向**，以下方式二选一：
+ **技术**导向：致力于改进某种通用技术，并在不同任务（或标准数据集任务）上进行验证，如神经网络的改进，zero shot方法改进等；
+ **任务**导向：致力于改进某种特定的问题或任务，如情感分类，皮肤病识别，图像翻译等。

****

确定大方向后，便获得了初始的关键词（如zero shot learning，Image-to-Image Translation等），按以下方式进行进行文献搜集，

+ **顶会顶刊关键词搜索**

   + 近三年顶会论文阅读，包括：[CVPR](http://openaccess.thecvf.com/menu.py)，[ICCV](http://openaccess.thecvf.com/menu.py)，[ECCV](http://openaccess.thecvf.com/menu_other.html)，[ICLR](https://openreview.net/group?id=ICLR.cc)，[NeurIPS](https://openreview.net/group?id=NIPS.cc)，[ICML](https://openreview.net/group?id=ICML.cc)等；（*在较广泛的范围内选题，也可以在大量泛读最新会议论文的基础上审视自己的兴趣以及业界研究热点的所在*）

   + 近五年顶刊论文阅读，包括：[TPAMI](https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=34)，[TIP](https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=83)，[IJCV](https://link.springer.com/journal/11263)等；

   注意事项：培养**对于优秀论文的鉴别能力**，以此来合理分配阅读时间。评价指标包括但不限于：论文出处（会议期刊级别）、类型（oral或poster）、引用量、作者（如Kaiming的文章多数很经典）。

+ **已有论文参考文献交叉搜索**

   + 由目前论文中的参考文献进行交叉搜索，可以找出相关的非近年发表的经典论文，以及题目中无相关关键词的必引论文；

   + 精读经典论文以及最新顶会顶刊工作的Related Work部分，按照作者的综述大量略读该领域文献，找出该领域发展脉络并总结；（**该过程非常重要，相当于构建一个‘论文空间’，每次读到新论文都要对其进行归类，自己工作的Idea也是这个空间中的一个点，也即某个发展方向的延伸或某几个方向的交汇。** 以生成式对抗网络为例，可将现有论文按如下方式大致归类：技术上分为对模型网络结构的设计和对损失函数的设计；任务上分为纯生成任务(强调生成器)和与其他任务如语义分割等的结合(强调对抗思想)；目标上分为解决模式崩溃等训练不稳定性问题、提升生成样本质量和提升其他任务性能等）。

+ **作者及研究组主页搜索**

   + 关注该领域活跃的作者，包括大佬级别和生力军，日常翻阅其主页（获取论文、代码、教程博客及其他动态）；

   + 观察某一研究者所做研究之间的相关关系，为自己的研究思路提供借鉴。

+ **其他搜索方式**

   + 利用[Arxiv](https://arxiv.org/)、[Google Scholor](https://scholar.google.com.sg/)、[dblp](https://dblp.uni-trier.de/)等搜索漏网之鱼。

***任务***：

+ 确定自己的研究大方向，按照以上方法进行文献调研，尽可能全地找到该领域的相关工作，以合理的方式建立索引；

+ 整理文档：概括该领域发展脉络；

+ 整理表格：记录每篇论文题目、出处、作者、单位、代码情况、主要贡献等；

+ 论文阅读：精读各领域经典论文（分类领域从AlexNet到DenseNet、目标检测领域从RCNN到YoLo、分割领域从FCN到MaskRCNN、生成领域从GAN到BigGAN等），在最新顶会列表上大量泛读（读摘要和Introduction决定是否精读，迅速了解该文章的主要创新点）。

## 3. 深度学习编程框架学习

学习资源：（*最好的学习方式便是安装配置好后自己动手尝试，遇到问题查英文官网上的官方文档，遇到报错查Google解决*）

+ TensorFlow
   + [中文版官方文档](https://www.w3cschool.cn/tensorflow_python/?)

+ PyTorch
   + [中文版官方文档](https://pytorch-cn.readthedocs.io/zh/latest/)

+ MXNet：
   + [动手学深度学习视频课程](https://www.bilibili.com/video/av42355860?from=search&seid=10327628739099351727)，李沐（*分类分割检测等均有实现实例，质量非常高*）
   + [动手学深度学习教科书](http://zh.gluon.ai/)，李沐


***任务***：

+ 学习TensorFlow、Pytorch、MXNet中的至少一个；

+ 安装配置基于Ubuntu + CUDA + CuDNN + Anaconda的深度学习环境，配置相关源以加速相关包的安装，安装相应的深度学习框架并测试；

+ 使用ssh或pycharm、VScode等编译器的远程调试功能，在后台远程连接实验室服务器；

+ 编写代码实现以下任务：

   + CIFAR10数据集分类，使用resnet50框架，体会有/无预训练模型的差异；

   + SD-198皮肤病数据集分类（注意数据读取效率），并以普通Resnet 50分类器为baseline提出三种改进策略，观察结果并分析有效性；

   + 训练Faster Rcnn （任意数据集），并在任意图像上测试；

   + 实现基本的生成式对抗网络，利用celebA数据集生成人脸图像，基于该基准，按照最近提出的方法继续改进。

## 4. 论文写作与rebuttal流程

+ latex相关：
   + [命令查询](http://www.mohu.org/info/symbols/symbols.htm)

+ **论文结构**


***任务***：选定某篇经典论文，分析其论文结构

+ **Rebuttal及Response**

## 5. 中英文邮件相关

+ **基本格式**

+ **注意事项**