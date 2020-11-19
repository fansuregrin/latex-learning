# learing latex

## Introduction
TeX（/tɛx/，常被读作/tɛk/，音译“泰赫”，“泰克”，写作“TEX”），是一个由美国计算机教授高德纳（Donald Ervin Knuth）编写的排版软件。TeX的MIME类型为application/x-tex，是一款自由软件。它在学术界特别是数学、物理学和计算机科学界十分流行。TeX被普遍认为是一个优秀的排版工具，尤其是对于复杂数学公式的处理。利用LaTeX等终端软件，TeX就能够排版出精美的文本以帮助人们辨认和寻找。

由tex衍生出的软件有`MacTex`、`TexLive`、`MikTex`等。

这里放置就是我练习的tex源码

## Installtion
### 1.Using Tex on Linux
可以安装[TexLive](https://www.tug.org/texlive/)，比如在`ArchLinux`上可以使用如下命令安装：
```
sudo pacman -S texlive-most texlive-langchinese
```
- texlive-most 包括Tex Live应用
- texlive-langchinese 包含 CTeX 宏集，提供了强大的中文处理功能

如果需要管理tex宏包，可以通过安装`texlive-localmanager-git`:
```
yay -S texlive-localmanager-git
```

### 2.Using Tex on MacOs
可以安装[MacTex](https://www.tug.org/mactex/)

### 3.Using Tex on Windows
可以安装[TexLive](https://www.tug.org/texlive/windows.html)或者[MikTex](https://miktex.org/)
