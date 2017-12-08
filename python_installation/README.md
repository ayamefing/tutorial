# 让我们从学习Python开始

我们终于要开始了！

但首先，让我们告诉你什么是 Python。Python 是一种非常流行的编程语言，可以用来创建网站、 游戏、 科学软件、 图形和很多很多其他的东西。

Python 起源于 1980 年代后期，该语言的重要目标是源代码的人类可读性 (而不是机器!)。 这就是为什么它看起来比其他编程语言简单得多。 这使得它易于学习，但不要担心，Python 也是真的很强大 ！

# Python的安装

> 需要说明的是，如果你已经熟悉Python的安装步骤，那你就无需看这章，直接跳到下一章好了。

> 本节基于 Geek Girls Carrots (https://github.com/ggcarrots/django-carrots) 的教程

Django 是用 Python 写的。 在 Django 中，我们需要使用 Python 语言去做所有的事情。 让我们从安装开始 ！ 我们希望您能安装 Python 3.4，所以如果你有任何以前的版本，你将需要将其升级。

### Windows系统

您可以从 https://www.python.org/downloads/release/python-343/ 网站上下载 Windows版的Python。 下载 * **.msi** 文件完成之后，你应该运行它 （双击它），并按照那里的指示。 重要的是记住 Python 的安装位置的路径 （目录）。 它以后将会被需要 ！

需要注意一件事情：在安装向导的第二步，选中“Customize”，向下滚动并确保选中“Add python.exe to the Path”选项，如下所示：

![别忘了增加 Python 到 Path](../python_installation/images/add_python_to_windows_path.png)

### Linux系统

很有可能你的系统已经默认安装了Python。要检查你是否安装了 （并且它是哪一个版本），打开控制台，并键入以下命令：

    $ python3 --version
    Python 3.4.3
    

如果你未曾安装过 Python 或者你想要一个不同的版本，你可以按如下所示安装它：

#### Debian 或 Ubuntu

在控制台中键入此命令：

    $ sudo apt-get install python3.4
    

#### Fedora

在您的控制台中使用此命令：

    $ sudo dnf install python3.4
    

#### openSUSE

在您的控制台中使用此命令：

    $ sudo zypper install python3


### OS X

你需要去到网站 https://www.python.org/downloads/release/python-343/ 然后下载 Python 安装程序：

  * 下载 *Mac OS X 64-bit/32-bit installer* 文件，
  * 双击 *python-3.4.3-macosx10.6.pkg* 以运行安装程序。

验证安装成功，请打开 *终端* 应用，运行 `python3` 命令：

    $ python3 --version
    Python 3.4.3
    

* * *

如果您有任何疑问，或如果出了错，你根本不知道该怎么办下一步-请询问你的指导 ！ 有时事情都不顺利，这时寻求其他更多经验的人的帮助会更好。
