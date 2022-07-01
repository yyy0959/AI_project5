# AI_project5
## 包含数据文件，四个ipynb文件和执行代码生成的文件
```
### lab5_txt_or_pic.ipynb
#### 1、仅使用图片，从头训练Resnet模型，三分类准确率60%
#### 2、仅使用文本，用BERT进行微调，三分类准确率72%
#### 3、仅使用图片，对ImageNet上与训练好的RESNET做linear probe，三分类准确率62%
#### 4、观察bert微调模型的预测结果，打印预测错误且困惑度比较大的图片文本
### lab5_txt_preprocess.ipynb
#### 仅使用文本，尝试对文本进行预处理，删除@某人和网页链接内容，再用bert微调，三分类准确率72%
### lab5_CLIP.ipynb
#### 仅使用图片，尝试使用OPENAI的CLIP模型直接做zero shot预测，计算图片与三句分别表达正面，负面和中立情感的句子之间的相似度，三分类准确率最高达到。
### lab5_txt_and_pic.ipynb
#### 1、使用图片和文本，图片端使用resnet提取特征，文本端使用bert，均做微调，使用concat进行拼接，三分类准确率72%
#### 2、使用图片和文本，图片端使用resnet提取特征，文本端使用bert，均做微调，使用attention计算他们和query向量的相似度作为权重动态加权，三分类准确率74%
```

