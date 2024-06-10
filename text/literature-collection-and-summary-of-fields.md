---
cover: >-
  ../.gitbook/assets/hujunyao_Research_reports_and_papers_on_the_desk_watercolor_sty_4b1c4e56-8883-47eb-b54c-476544e2d679.webp
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 文献搜集与特定领域发展情况总结

在Idea形成之前，应首先确定一个**大方向**，以下方式二选一：

* **技术**导向：致力于改进某种通用技术，并在不同任务（或标准数据集任务）上进行验证，如神经网络的改进，zero shot方法改进等；
* **任务**导向：致力于改进某种特定的问题或任务，如情感分类，皮肤病识别，图像翻译等。

***

确定大方向后，便获得了初始的关键词（如zero shot learning，Image-to-Image Translation等），按以下方式进行进行文献搜集，

*   **顶会顶刊关键词搜索**

    * 近三年顶会论文阅读，包括：[CVPR](http://openaccess.thecvf.com/menu.py)，[ICCV](http://openaccess.thecvf.com/menu.py)，[ECCV](http://openaccess.thecvf.com/menu\_other.html)，[ICLR](https://openreview.net/group?id=ICLR.cc)，[NeurIPS](https://openreview.net/group?id=NIPS.cc)，[ICML](https://openreview.net/group?id=ICML.cc)等；（_在较广泛的范围内选题，也可以在大量泛读最新会议论文的基础上审视自己的兴趣以及业界研究热点的所在_）
    * 近五年顶刊论文阅读，包括：[TPAMI](https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=34)，[TIP](https://ieeexplore.ieee.org/xpl/mostRecentIssue.jsp?punumber=83)，[IJCV](https://link.springer.com/journal/11263)等；

    注意事项：培养**对于优秀论文的鉴别能力**，以此来合理分配阅读时间。评价指标包括但不限于：论文出处（会议期刊级别）、类型（oral或poster）、引用量、作者（如Kaiming的文章多数很经典）。
* **已有论文参考文献交叉搜索**
  * 由目前论文中的参考文献进行交叉搜索，可以找出相关的非近年发表的经典论文，以及题目中无相关关键词的必引论文；
  * 精读经典论文以及最新顶会顶刊工作的Related Work部分，按照作者的综述大量略读该领域文献，找出该领域发展脉络并总结；（**该过程非常重要，相当于构建一个‘论文空间’，每次读到新论文都要对其进行归类，自己工作的Idea也是这个空间中的一个点，也即某个发展方向的延伸或某几个方向的交汇。** 以生成式对抗网络为例，可将现有论文按如下方式大致归类：技术上分为对模型网络结构的设计和对损失函数的设计；任务上分为纯生成任务(强调生成器)和与其他任务如语义分割等的结合(强调对抗思想)；目标上分为解决模式崩溃等训练不稳定性问题、提升生成样本质量和提升其他任务性能等）。
* **作者及研究组主页搜索**
  * 关注该领域活跃的作者，包括大佬级别和生力军，日常翻阅其主页（获取论文、代码、教程博客及其他动态）；
  * 观察某一研究者所做研究之间的相关关系，为自己的研究思路提供借鉴。
* **其他搜索方式**
  * 利用[Arxiv](https://arxiv.org/)、[Google Scholor](https://scholar.google.com.sg/)、[dblp](https://dblp.uni-trier.de/)等搜索漏网之鱼。

_**任务**_：

* 确定自己的研究大方向，按照以上方法进行文献**搜集**，尽可能全地找到该领域的相关工作，以合理的方式建立索引；
* 整理文档：概括该领域**发展脉络**（按照领域的各个发展方向分别整理，遵循以下格式：第一篇论文的主要思路，存在问题1和问题2；后一篇论文分析问题1可以有什么解决，怎么解决的；另一篇论文如何解决了问题2；在解决问题1和2的同时又引入了新的问题，后又被如何解决）；
* 整理**表格**：记录每篇论文题目、出处、作者、单位、代码情况、主要贡献等；
* 论文阅读：**精读**各领域经典论文（分类领域从AlexNet到DenseNet、目标检测领域从RCNN到YoLo、分割领域从FCN到MaskRCNN、生成领域从GAN到BigGAN等），在最新顶会列表上**大量泛读**（读摘要和Introduction决定是否精读，迅速了解该文章的主要创新点）。
