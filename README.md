# AI-期中報告
組員：11218201方玄伶、11218202呂蕙妤

Colab實用教程

目录

1.Colab是什么？

2.Colab的基本配置

3.Colab模型训练

4.进阶使用

<br />
Colab是什么？

Google Colab是一个免费的云服务并支持免费的GPU，可以：

1.提高你的 Python 语言的编码技能。

2.使用 Keras、TensorFlow、PyTorch 和 OpenCV 等流行库开发深度学习应用程序。

3.Colab 与其它免费的云服务最重要的区别在于：Colab 提供完全免费的 GPU，对学生党进行AI学习提供便利。

Colab是Google的且服务器在国外

1.如果不能使用Google，推荐使用Kaggle（国内也能访问）👉免费的深度学习GPU环境Colab和Kaggle搭配使用

2.如果可以上Google，那就继续往下看学习Colab用法！

<br />
Colab的基本配置

1.登录 Google Drive

2.在 Google Drive 上创建文件夹，我创建的是名为人工智慧的文件夹

![image](https://github.com/hy189/AI/blob/111d1455217bcf76793b8287c5bd7d4caeb31888/%E8%9E%A2%E5%B9%95%E6%93%B7%E5%8F%96%E7%95%AB%E9%9D%A2%202024-10-31%20153926.png)

3.创建新的Colab笔记（Notebook），通过 右键点击 > More > Colaboratory 步骤创建一个新的笔记

通过点击文件名来重命名笔记

4.打开GPU

Edit > Notebook settings 或者进入 Runtime > Change runtime type，然后选择 GPU 作为 Hardware accelerator（硬件加速器）。

5.使用 Google Colab 运行基本的 Python 代码

这个倒是不常用，使用这个功能类似jupyter notebook，而我们要跑的代码基本是已经编辑好的工程项目。利用colab主要是想通过GPU加速更快的训练。

6.在创建的文件夹页面上传你的整个要跑的文件(包括数据集)，右击选upload fold 或者直接拖拉也行
