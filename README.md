# 小红书评论数据集

## 介绍
我们利用爬虫来对小红书网页笔记进行爬取评论，然后讲爬取的数据保存到以当前时间命名的csv文件中，再经过数据清洗、预处理、标注等操作，最后分为了训练集、验证集、测试集比例为6:2:2。

## 文件结构如下：
RedBookletReview
├── RedBookletReview
  ├── dev.tsv
  ├── test.tsv
  ├── train.tsv
└── results
  └── RedBookletReview.tsv

        