# 步骤一:收集数据
收集数据是解决任何监督机器学习问题的最重要步骤。 只有构建好的数据集您的分类器才能表现的好。

如果您没有想要解决的特定问题，并且只对一般的文本分类感兴趣，那么可以使用大量的开源数据集。 您可以在我们的[GitHub](https://github.com/google/eng-edu/blob/master/ml/guides/text_classification/load_data.py)仓库中找到其中一些链接。 另一方面，如果您要解决特定问题，则需要收集必要的数据。 许多组织提供用于访问其数据的公共API - 例如，[Twitter API](https://developer.twitter.com/en/docs)或[NY Times API](http://developer.nytimes.com/)。 您可以利用这些来解决您要解决的问题。

以下是收集数据时需要记住的一些重要事项：

*  如果您使用的是公共API，请在使用之前了解API的限制。 例如，某些API会对您进行查询的速率设置限制。
*  您拥有的培训示例（在本指南的其余部分中称为示例）越多越好。 这将有助于您的模型更好地概括。
*  确保每个类或主题的样本数量不会过度失衡。 也就是说，每个类中应该有相当数量的样本。
*  确保您的样品充分覆盖可能的输入空间，而不仅仅是常见情况。

在本指南中，我们将使用Internet电影数据库[（IMDb）](http://ai.stanford.edu/~amaas/data/sentiment/)电影评论数据集来说明工作流程。 该数据集包含人们在IMDb网站上发布的电影评论，以及指示评论者是否喜欢该电影的相应标签（“正面”或“否定”）。 这是情绪分析问题的典型例子。

