# 这是NLP的期末大作业：基于潜在语义索引算法-LSI的电影检索
### 潜在语义索引(LSI)概述:潜在语义索引(Latent Semantic Indexing,以下简称LSI)，有的文章也叫Latent Semantic  Analysis（LSA）。其实是一个东西，后面我们统称LSI，它是一种简单实用的主题模型。LSI是基于奇异值分解（SVD）的方法来得到文本的主题的。
详细介绍见：https://www.cnblogs.com/pinard/p/6805861.html
### 本次电影检索分为**中文电影**检索和**英语电影**检索


# 文档说明
## 0. 环境（不用一定一样）
anaconda  version 1.7.2

python    version 3.8.3


## 1. 数据
名称：**KaggleMovie.csv**    
来源：https://www.kaggle.com/datasets/devendra45/movies-similarity

名称：**DouBanMovie.csv**  
来源：https://sec.douban.com/   /---- 手动爬取-----/

## 2. 文件
**input**文件夹：存放处理文件KaggleMovie.csv和DouBanMovie.csv

**KaggleMain.pynb**文件：处理KaggleMovie.csv的主函数，由jupyter笔记编写，见代码注解

**DouBanMain.pynb**文件：处理DouBanMovie.csv的主函数，由jupyter笔记编写，见代码注解

**script**文件：由于涉及绘制词云图，wordcloud缺少中文字体，需要导入，这里导入simfang.ttf字体
