# 介绍
文本分类算法是大规模处理文本数据的各种软件系统的核心。 电子邮件软件使用文本分类来确定传入邮件是发送到收件箱还是过滤到垃圾邮件文件夹中。 论坛使用文本分类来确定评论是否应标记为不当。

这是主题分类的两个示例，将文本文档分类为预定义的一组主题。 在许多主题分类问题中，这样的分类问题主要基于文本中的关键字。
![](../Pic/introduction/TextClassificationExample.png)

#### 图1：主题分类用于标记传入的垃圾邮件，这些邮件被过滤到垃圾邮件文件夹中。

另一种常见的文本分类是```情感分析```，其目的是识别文本内容的正负性：表达意见好坏的类型。 这可以采取二进制喜欢/不喜欢评级的形式，或更精细的选项集，例如1到5的星级评级。情绪分析的示例包括分析Twitter帖子以确定人们是否喜欢黑豹电影，或者 从沃尔玛评论中推断出普通大众对耐克新品牌鞋的看法。

本指南将教您一些解决文本分类问题的关键机器学习最佳实践。 这是你将学到的东西:

*  使用机器学习解决文本分类问题的高级的端到端工作流程
*  如何为文本分类问题选择正确的模型
*  如何使用TensorFlow实现您的选择模型

