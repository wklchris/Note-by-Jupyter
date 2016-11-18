# Introduction [ 引言 ]

Most notes here are in "ipynb" format, which is a abbreviation for "**Ipy**thon **N**ote**b**ook". It will provide you a comfortable reading experience via your web browser. 
**They are created by Jupyter.**  
【这里的大部分笔记都是使用 "ipynb" 格式的。它是 "**Ipy**thon **N**ote**b**ook" 的缩写。它仅仅要求你有一个网页浏览器，就能提供给你舒适的阅读体验。
**它们由 Jupyter 创建。**】

Quick links for my notes: 【笔记传送门】

- Python 3：
  - [Numpy](https://github.com/wklchris/Note-by-Jupyter/blob/master/Python/Numpy.ipynb)
  - [Pandas](https://github.com/wklchris/Note-by-Jupyter/blob/master/Python/Pandas.ipynb)
  - [Matplotlib](https://github.com/wklchris/Note-by-Jupyter/blob/master/Python/Matplotlib.ipynb)

# What is Jupyter？ [ 什么是Jupyter? ]

Jupyter ([http://jupyter.org/](http://jupyter.org/)) is: 

> a web application that allows you to create and share documents that contain **live code, equations, visualizations** and explanatory text. 

It supports **over 40** kinds of programming languages. I'll use it for Python 3 and R in this repository.

【 Jupyter 它是："一个允许你创建和分享包含**代码、公式、可视化图表**，以及解释性文字的文件的网络应用。"它支持**超过40种**编程语言。我会在这个 GitHub 仓库中展示关于 Python 3 和 R 的内容。】

# How to install Jupyter? [ 怎样安装Jupyter? ]

You can find the official installing guide on [https://jupyter.readthedocs.io/en/latest/install.html](https://jupyter.readthedocs.io/en/latest/install.html). Or you can just follow as below (if you have installed Python kernel):

【 你可以找到[官方安装指导](https://jupyter.readthedocs.io/en/latest/install.html)，或者你可以按照我在下面写的做（如果你已经在电脑上安装了 Python ）：】

    pip3 install --upgrade pip
    pip3 install jupyter

Then you can run Jupyter by input this in the command line:  
【 然后用下述命令行指令运行 Jupyter 】

    jupyter notebook

Your web browser will be opened automatically and the interface of Jupyter will show up.  
【 你的网页浏览器会自动打开，并将 Jupyter 的界面呈现给你。】

# Install R kernel if you need [ 安装 R 语言内核（如需） ]

Visit [IRkernel website installation guide](https://irkernel.github.io/installation/) to get ready for using R in Jupyter! Simply speaking, it requires you to input these lines in the R console:

【访问[IRkernel安装指导](https://irkernel.github.io/installation/)来设置你的 Jupyter，使之能够与 R 协同工作。简单说来就是在 R 控制台输入以下几行：】

    install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))
    devtools::install_github('IRkernel/IRkernel')
    IRkernel::installspec()

# Create a New File and Get Start! [ 创建新文件并开始吧! ]

On the top right corner of the Jupyter webpage, you will see a "New" drop-down menu. You will surely see "Python" in it. If you want to work with other kinds of kernel, please tend to Jupyter official website for help.   
【 在页面的右上角，你会看到一个名叫“ New (新建) ” 的下拉菜单，其中必定含有“ Python ” 这个选项。如果你想调用其他语言的内核，请前往 Jupyter 官方站点寻找帮助。 】