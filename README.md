# dogs-vs-cats
[猫狗大战](https://www.kaggle.com/c/dogs-vs-cats)是Kaggle比赛的经典项目样例，也是本次P7需要完成的毕业项目，项目要求超过Kaggle排名Top —10%[dog_vs_cat](https://github.com/nd009/capstone/tree/master/dog_vs_cat)。  

### 项目资料
数据集下载：[训练集 + 测试集](https://www.kaggle.com/c/dogs-vs-cats/data)  ，kaggle一共提供了两个数据集train与test。其中train set包含25000个样本，cat和dog各12500个。
![](https://i.imgur.com/kS76chv.jpg)  
test set包含12500张图片，但没有分类。  
![](https://i.imgur.com/BW4ga6N.jpg)

### 神经网络模型
完成本次项目采用ResNet50模型，并对模型进行Dropout，进行迁移学习，ResNet曾在2015年imageNet比赛中获得头名，我将ResNet模型进行进一步优化。并在loss取得一部分的优化效果。

![image](http://img.blog.csdn.net/20180114184946861?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbGFucmFuMg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)
![image](http://img.blog.csdn.net/20180114205444652?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvbGFucmFuMg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

### 文件结构
- file_result.csv 测试集结果
- model_display.png 神经网络模型结构图
- cat.vs.dog.ipynb/cat.vs.dog.html 程序运行文件
- training_log2.txt 训练log文件
- 机器学习工程师纳米学位毕业项目.pdf 提交的毕业报告
 
