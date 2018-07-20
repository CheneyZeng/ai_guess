# 神经网络学习“你拍我猜” —— 你拍照，AI猜
[//]: # (Image References)

[image1]: ./images/dog.png "Sample Output"
[image2]: ./images/dog2.png "VGG-16 Model Keras Layers"


## 项目概述

欢迎来到神经网络学习“你拍我猜”项目！在这一项目中，在这个项目中，你将学习利用神经网络来分类照片中是狗狗，是猫猫，还是人。

![Sample Output][image1]

我们的目标是，当你完成这一项目时，你将可以理解，设计数据处理管道完成各式各样的任务所面临的挑战，实现正向、反向及交叉熵函数。你将会完成你自己的分类网络！现在我们就开始吧！


## 项目指南

### 步骤

1. 克隆存储库并打开下载的文件夹。

 ```	
git clone https://github.com/CheneyZeng/ai_guess.git
```

2. 安装必要的 Python 依赖包


	对于 __Mac/OSX__：
	
	```bash
	conda env create -f requirements/ai-mac.yml
	source activate ai_guess
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	对于 __Windows__：
	
	```bash
	conda env create -f requirements/ai-windows.yml
	activate ai_guess
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
	```
	
3. 打开 notebook

```
jupyter notebook guess_ai.ipynb
```

__注意：__ 我们虽然已经实现了一些代码，让你更快地开始工作，你仍需要实现额外的功能，以回答 notebook 中所有的问题。
__除非有要求，否则不要修改任何已经包含的代码。__

## 项目评审

你的项目将会由优达学城的审阅者依据次项目的[评审标准](https://review.udacity.com/#!/rubrics/2093/view)进行审阅。请仔细阅读，并在提交之前自我评估你的项目。你必须通过了规则中的所有要求，才会审核通过。

## 项目提交

当你准备好提交你的项目时，将下列文件整理并压缩成一个文件，以便上传。

- 代码完整可运行的文件 `ai_guess.ipynb`，所有的代码块都要执行并展示结果，并要求回答所有问题
- 将你的 notebook 导出为 HTML 以及 py 格式，并以 `ai_guess.html` 以及 `ai_guess.py` 命名
- 任何用于项目中，并且并非由我们为这一项目提供的额外数据图片。

此外，你也可以通过 GitHub 连接提交项目。
