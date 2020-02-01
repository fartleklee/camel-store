# camel-store
骆驼小店-基于Python/Django的微信小程序商城。

------------

## 概述

现在项目分为 4 个 github 项目仓库，

1. `camel-store`，也就是本仓库，主要是发布统一版本、存放项目文档，以及作为大局沟通渠道。
    1. `docs` 目录放的是文档。
    1. `CSEPs` 目录放的是骆驼小店增强改进提案(Camel Store Enhancement Proposals)，是向 `Python` 项目的 PEP 学习的一种项目管理手段，对此不太了解的朋友可以看看这篇[python中的PEP是什么？怎么理解？（转）](https://www.cnblogs.com/abella/p/10056875.html)。
    1. `admin`、`api`、`wxapp`，三个目录是通过 submodules 方式引入的三个项目，分别对应管理后台、API和小程序三端。
1. [`admin`](https://github.com/gzqichang/camel-store-admin)是项目管理后台，由基于`Ant design pro`开发，使用的是`React.js`框架。
1. [`api`](https://github.com/gzqichang/camel-store-api)是API部分，使用`Python`编程语言开发，主要使用了`Django`和`Django-rest-framework`框架。
1. [`wxapp`](https://github.com/gzqichang/camel-store-wxapp)是小程序部分，使用了`WePY`框架。

## 技术理念

这不是一个库，是一个应用项目，所以追求的是下载、安装/编译，然后就可以提供商业服务。所以它整体是难以在代码级别被集成到别的项目中去，它的技术理念是对扩展、替换开放，并提供相应的机制（但目前做得还不够好）。如果通过修改已有代码的方式来实现自己的业务逻辑，可能会导致难以升级到新的版本。


## 在本机体验
文档在编写中，先看一下 [docs](https://github.com/gzqichang/camel-store/tree/master/docs)。

1. [Dev on MacOS](https://github.com/gzqichang/camel-store/blob/master/docs/dev-on-mac.md)
1. Dev On Windows. to be done.

## 参与开发

类似其他 github 项目，针对`admin`、`api`、`wxapp`三个仓库进行 fork，修改和测试后，欢迎提交 PR。

## 官方支持

我们建立了一个官方微信群，先扫下面的二维码，加好友后说“我要加入 camel-store 官方群”即可。

![企业微信](contact-qrcode.png)
