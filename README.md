# 基于jieba动态调整字典和词频的电子病历分词实践

## （一）总体说明

这是一个电子病历分词的小项目，是用jieba来实现的。为了提高分词的准确性，加载了医疗行业命名实体识别字典、自定义字典，并运用了正则表达式对特殊的数据词语进行匹配，最后用停用词表进行过滤，输出更干净的结果。

source_data 这个路径下是200篇文档，其中包含“txtoriginal”英文的文档是电子病历文档，总共100篇。这个小实践就是要对这100篇电子病历进行分词。

使用的Python编辑器为 wingide6.

欢迎移步[我的博客](https://www.cnblogs.com/Luv-GEM/p/10534713.html)看更详细地说明。

## （二）实践过程

这个小实践分为三步：

### 1 jieba直接分词

代码文件: cut_direct.py

分词结果：cut_direct.txt

### 2 加载医疗命名实体识别字典

命名实体识别字典：DICT_NOW.csv

代码文件：cut_dict.py

分词结果：cut_dict.txt

### 3 自定义字典、正则表达式匹配和停用词过滤

命名实体识别字典：DICT_NOW.csv

自定义字典：userdict.txt

停用词表：stop_words.txt

代码文件：cut_stopwords.py

分词结果：cut_stopwords.txt

正则表达式匹配结果：regex_dict.txt


**资料整理得比较乱，以后有时间再整理了。**
