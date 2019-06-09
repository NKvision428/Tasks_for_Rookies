# Tasks_for_Rookies

欢迎来到[计算机视觉实验室](http://cv.nankai.edu.cn/)新手村。新手任务共分为以下几个部分：

>机器学习与深度学习基础

>论文阅读

>文献搜集与特定领域发展情况总结

>深度学习编程框架学习与算法实现

>论文写作与rebuttal流程

>中英文邮件相关


## 1. 机器学习与深度学习基础

+ [机器学习（西瓜书，周志华著）](https://www.zhihu.com/question/39945249)；

任务：细读第二到第十四章，并任选一章整理分析。

+ [深度学习（花书，Goodfellow，Bengio等著](https://github.com/zsdonghao/deep-learning-book/blob/master/dlbook_cn_public.pdf)；

任务：从第五章以后精读（尤其是7、8、9、11、12），理解并归纳机器学习中的正则化方法、优化方法以及卷积等操作。英语基础好的同学最好看英文版，以熟悉相关术语。

+ [斯坦福CS231n CNN for Visual Recognition](https://www.bilibili.com/video/av53754154?from=search&seid=6020411155113851809)，总时长约20小时；

任务：完成至少三次课堂作业，同时锻炼英语能力。


## 2. 文献搜集与特定领域发展情况总结

在Idea形成之前，应首先确定一个**大方向**，以下方式二选一：
+ 技术导向：致力于改进某种通用技术，并在不同任务（或标准数据集任务）上进行验证，如神经网络的改进，zero shot方法改进等；
+ 任务导向：致力于改进某种特定的问题或任务，如情感分类，皮肤病识别，图像翻译等。

****

确定大方向后，便获得了初始的关键词（如zero shot learning，Image-to-Image Translation等），按以下方式进行进行文献搜集，

+ 顶会顶刊关键词搜索   

   + 近三年顶会论文阅读，包括：[CVPR](http://openaccess.thecvf.com/menu.py)，[ICCV](http://openaccess.thecvf.com/menu.py)，[ECCV](http://openaccess.thecvf.com/menu_other.html)，[ICLR](https://openreview.net/group?id=ICLR.cc)，[NeurIPS](https://openreview.net/group?id=NIPS.cc)，[ICML](https://openreview.net/group?id=ICML.cc)等；（*在较广泛的范围内选题，也可以在大量泛读最新会议论文的基础上审视自己的兴趣以及业界研究热点的所在*）

   + 近五年顶刊论文阅读，包括：[TPAMI](https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=34)，[TIP](https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=83)，[IJCV](https://link.springer.com/journal/11263)等；

### 论文阅读日常




顶会(近三年)顶刊(近五年)关键词搜索
根据1中论文参考文献进行搜索
由1，2中论文相关工作介绍，归纳出该领域专家(或研究组)，

3深度学习编程框架学习

学习三大框架之一

编写代码实现cifar10数据集分类，使用resnet50框架，分别使用无/有预训练模型

编写代码实现sd198上的分类(注意数据读取速度)，并基于普通resnet 50分类器的baseline提出三种改进策略，观察结果并分析有效性

编写代码训练faster rcnn (任意数据集)，并在任意图像上测试

编写代码实现基本的生成式对抗网络，利用celebA数据集生成人脸图像；继续改进。

4特定方法编程实现

手写实现resnet50，wgan，数据读取策略，评价指标等，分析可以改进之处。

5论文写作与rebuttal流程

latex学习

论文结构

rebuttal注意事项

6中英文邮件相关

基本格式

注意事项