### 1、介绍

这是通用的NLP任务训练框架，基于pytorch和transformers框架搭建。

### 2、环境需求

python >= 3.5

pytorch==1.9.0

numpy==1.17.0

transformers==3.0.0

### 3、使用
所有新创建的任务都在task文件夹下，可以参考examples文件夹下的例子

需要修改的代码部分：  

（1）创建模型动态计算图  

（2）数据处理部分代码  

（3）配置config类的任务所需超参数  

写完这三个部分的代码，整个模型训练基本就可以运行起来了  

### 4、已新增的example

examples文件夹下：

命名实体识别任务：ner_example.py  
成语阅读理解任务：cloze_example.py  


**框架后续将继续完善**  

添加更多不同NLP任务的examples  

添加各种attention注意力模块  

添加常用的NLP模型的模块代码  

添加各种loss函数的代码  

**可扩展为兼容tensorflow**



