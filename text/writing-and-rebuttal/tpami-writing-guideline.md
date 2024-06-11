# TPAMI写作指南

## 宗旨

* **学会模仿**
  * 加上参考文献，总篇幅14-15页为宜
  * 检索、阅读、总结，进行模仿学习
    * 如果已知某篇初始种子文献，可围绕其展开检索
    * 对比相关主题的TPAMI文章、延伸ML主题的TPAMI文章、其他的文章
    * 对比直接投稿的与会议改期刊投稿的文章
  * 研究每个章节的写法和研究思路
    * 每个章节应该怎么构思、联系，注重前后逻辑
    * 每个段落通常需要多少字/行才能讲清楚一件事情，不宜过多过少
    * 第一句话到最后一句话如何表达，才能使得文章清楚明白，没有废话
  * 若为会改刊，应当指出对会议版本的具体改动（摘要、引言贡献提及部分）
  * 考虑不同级别读者的视角和感受，内容描述清晰、逻辑通顺
* **学会管理**
  * 合理预估期刊的撰写/修改时间需要多久，多从后往前看，即从论文撰写的整体进度来考察当前进展是否得当，思考距离最终结果还差什么
  * 在写作初期就需要知晓整篇论文应该需要完成哪些补充工作，工作量应提前进行规划，并体现在论文中，空出需要撰写的部分，并留出自己补充与请他人修改的时间
  * 尽可能全面、细致地思考写作、实验中可能遇到的困难，多角度思考潜在的风险和可能的解决办法，以积极的心态和行动面对
  * 期刊扩展版本在写作过程中应体现修改进度，如用红色和黑色分别表示为已修改的段落与原会议版本的段落，使得进展清晰明了

## Idea相关

### 方法

* 思考方法时，思维和视野需打开
* 总结任务和方法时，要尽可能1-3句话说明白
* 设计绘制好pipeline，绘制方法路线图，起到提纲挈领作用，便于自己思考和相互交流打磨
* 针对不同的研究对象，有不同的研究思路，但相同的是都要对现有数据做足分析
  * 做方法的工作，可以收集现在SOTA代码的错误样本，针对性地统计分析，并在SOTA上提出改进方法
  * 做数据集的工作，数据集重点阐述数据集统计信息对接下来的任务的启发

### 贡献

* 加数据集：在更多的数据集上进行实验，使得模型所能应用的不同数据范围上表现良好
* 改进模块：进一步提升模块的性能
* 会议对比：针对会议版本的模型，是否需要加入对比实验作为一组对比数据，需要按实际情况进行考量，加入对比可以体现期刊版本模型的改进效果
* 超参讨论：设置不同的超参数分析器对模型的性能影响
* 下游应用：考虑模型在下游应用的表现，需要多少篇幅和表格才能说明其对该任务的有效性
* 相关工作补充与整理
* 结果可解释性分析
* 结果可视化展示
* 结果错例可视化分析

## 写作相关

### 标题

* 扩展版本应与会议版本有所区别：原论文标题应作何修改、当前修改是否得当、修改后的标题能否突出论文的重点、同类文章有无起标题的类似套路，斟酌用词

### 作者

* 明确作者身份，IEEE会员级别包括：会员（Member）、高级会员（Senior Member）和会士（Fellow）
* 明确作者顺序，标题下方姓名顺序与首页左下角脚注顺序一致
* 明确作者信息，学校写全称，确保地址、名称、邮编、邮箱信息正确

### 摘要

* 一个词组不应该重复出现
* 若为会改刊，应当指出对会议版本的具体改动

### 关键词

* 涉及到期刊分给哪个副编辑（Associate Editors, AE）和审稿人，也涉及到发表后在搜索引擎的检索效果
* 三到五个关键词，一行以内，一个词组不宜过长

### 引言

* 若为会改刊，应当指出对会议版本的具体改动
*   准确说明扩展期刊的贡献有多少、以尽可能细的粒度阐述贡献，提升说服力，描述要能够吸引人，比较两种实验结果说明：

    > * 在x个任务上进行了实验
    > * 在x个任务（a任务、b任务、c任务...）共x个数据集上进行了实验

### 相关工作

* 引用要求
  * 过于早期的旧文献不轻易引用（某领域开山之作除外，如DDPM、LDM）
  * 非直接相关的文献不轻易引用（包括同门发表的论文）
  * 选择投哪个期刊，该期刊的参考文献需达到一定的比例
  * 近2年的参考文献占比尽量大于1/3，确保实时性
  * 关注潜在审稿人、相关领域专家团队最新工作，也要关注arXiv更新的论文
  * 参考文献数量通常80-90篇为宜，某些领域可能稍多一些，不宜超过100
  * 对所引文献进行正确评价，理性考虑其优势和局限性，不过分夸大，也不恶意贬低
* 写作要求
  *   避免一句话连续引用很多篇文献，避免随意拼凑嫌疑，需摘取真正重要的文献，并讲透其内在逻辑关系，避免出现如下类似情况：

      > * 堆砌文献：xx方法\[ABCDEF]
      > * 简单总结：A提出xxxx，B提出xxxx，C提出xxxx
  * 注重引用格式、确保bibtex的会议和期刊引用格式正确，注意google scholar导出内容不一定准确，最好是进入对应会议期刊官网或该实验室/作者官网确认无误。

## 图表相关

* 首要准则：直观、简洁、清晰、紧凑
* 表达内容：每张图有其存在意义，内容饱满、给出的信息要给人启发性、有说服力
* 表现形式：不能过于枯燥单调，要能吸引人，不能仅仅简单呈现结果。表格个数不宜过多，相同类型的图表展示适当合并，
* 反复琢磨：扩展期刊版本的图表应与会议版本有所改进，特别是图/表一，应力求以更加清晰明了的表达方式使审稿人与读者快速了解文章意图，图表形式需要尽可能反复迭代优化、花时间挑图、改图\