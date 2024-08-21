# 简单介绍

`Gitbook`是什么？其实用一句话就可以概括，它是一个 **能将使用 Markown 语法的 `md` 格式文档，快速制作成各种格式电子书的工具**。

常被用于编写文档或者电子书，特点是方便简洁，易于使用。只要熟悉轻量级标记语法的 `Markdown`  语法，就能使用Gitbook 来制作各种格式的电子书。

Gitbook 生成电子书主要有三种方式：

1. `gitbook-cli` 命令行操作,简洁高效,适合从事软件开发的相关人员。
2. `gitbook-editor` 编辑器操作,可视化编辑,适合无编程经验的文学创作者。
3. `gitbook.com` 官网操作,在线编辑实时发布,适合无本地环境且科学上网的体验者。

本文主要讲解第一种 gitbook-cli 命令行操作流程。



> [!TIP]
>
> 因为`gitbook-cli`停止维护了，所以在新版本的nodejs环境安装gitbook-cli会出现许多问题，比如[TypeError: cb.apply is not a function](https://blog.csdn.net/sinat_31057219/article/details/112506883)和`gitbook init`报TypeError [ERR_INVALID_ARG_TYPE](https://blog.csdn.net/qq_33641175/article/details/122508473)，要么降级到对应的nodejs版本使用，要么像前面两个链接里的那样去修改程序代码以使程序正常运行。而Honkit是一个仍然在更新的Gitbook分支，关于HonKit的介绍，可以去他的[github页面](https://github.com/honkit/honkit)或者[文档](https://honkit.netlify.app)查看。



**参考：**[JiangMing-Gitbook详细教程](https://jiangminggithub.github.io/gitbook/)、[GitBook使用教程](https://blog.csdn.net/raspi_fans/article/details/129570510)、[GitBook简明教程](https://www.chengweiyang.cn/gitbook/)、[云原生Gitbook文档](https://www.zhaowenyu.com/gitbook-doc/)、 [gitbook/honkit的快速入手](https://blog.csdn.net/LoveZoeAyo/article/details/131355819)、[MarkDown官方教程](https://markdown.com.cn/basic-syntax/)



<!-- ex_nonav -->
<!-- ex_nolevel -->
