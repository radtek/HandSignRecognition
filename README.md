HandSignRecognition
===================

recognition engine of handwritten images


使用说明(How to use)：
### 1. 文件菜单：你可以选择你指定目录下的.pcx文件，进行查看。

### 2. PCX查看菜单：你可以对图片进行放大处理以及二值化处理。
### 3. 特征提取|估值菜单中：按顺序1,2,3先后选取训练样本（这里需要选择测试类型：是开测试还是闭测试），特征提取以及均值与方差的计算。
### 4. 分类测试菜单栏：在对样本进行训练学习后：如果是开测试，可以对测试样本分别同Bayes，最近邻，K近邻法进行测试；若为闭测试，则只能进行Bayes测试。你还可以任意选取一个未知样本进行Bayes，最近邻，K近邻法测试。在K近邻测试的时候，你还可以查看k值与识别率的函数关系图。
### 5. 帮助菜单：可以查看使用说明和程序相关点。

附注：开发环境是VS2010，C#。运行前先将DocLib下面的FreeImage.dll放到C:\Windows\System32下面为Release调试