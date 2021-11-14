张泽鹏（redraiment）
====

## 个人简介

* 姓名：张泽鹏
* 网名：redraiment
* 社交：redraiment@gmail.com
* 工作：外企（道富） ⇒ 创业 ⇒ 互金（51） ⇒ 制造（阿里）

## Emacs结缘

### 入坑

原先长期使用Vim，结果习惯成自然——无论在何处输入完都会习惯性地按`ESC`——觉得自己被软件操控，于是从Vim党叛逃。

我期待新的编辑器没有那么多条条框框，可以简单地当成Notepad来用，需要高级功能时可以随时调用。

在比对过UltraEdit、EditPlus、jEdit、Notepad++等多款编辑器后，最终选择了Emacs——它是最符合我的需求的。

### 学习

我的学习过程很普通，就是照着软件内的文档依次读了一遍：

1. Emacs Tutorial：`C-h t`
2. [GNU Emacs Manual](https://www.gnu.org/software/emacs/manual/html_node/emacs/index.html)
3. [An Introduction to Programming in Emacs Lisp](https://www.gnu.org/software/emacs/manual/html_node/eintr/index.html)
4. [Emacs Lisp Reference Manual](https://www.gnu.org/software/emacs/manual/html_node/elisp/index.html)

## 日常工作

### 用途

除了偶尔启动IDE写一些Java或Kotlin的代码，Emacs几乎承包了我日常所有的编辑工作。近期开发Clojure、JavaScript、Python以及写Markdown较多。

### 配置

我的`~/.emacs.d`目录下包含以下三类配置：

1. Emacs本身的配置。
2. 扩展的工具函数。
3. Emacs之外的配置。

第一类Emacs本身的配置比较少，主要是界面调整和快捷键调整。我的Emacs界面比较简洁，隐去了除编辑框之外的所有功能（例如工具栏、菜单栏等）。配置中通过[use-package](https://github.com/jwiegley/use-package)加载一些三方package（例如cider、haskell-mode等）并做一些简单配置。

第二类日常工作积累下来的Emacs Lisp函数或Yasnippet模板。例如JSON格式化、代码转图片、一键运行Clojure函数的测试用例等。我会不定期地把日常工作中会频繁用到的操作写成Emacs Lisp函数，就像有些用MacBook的小伙伴会用Alfred，只是我把Emacs当成统一的工作入口。

第三类与Emacs无关，我会把诸如gitconfig、pip.ini、npmrc、tmux.conf等其他工具的配置文档也都放到`~/.emacs.d/config`目录下统一管理。因为用Emacs时间比较就，期间换过很多次电脑，之前要花不少精力在新电脑上安装和配置软件，所以就把所有常用工具的配置放到`~/.emacs.d`统一管理，也方便跨电脑同步配置。

## 经历分享

### 学习方式

最好的学习方式就是『玩』——用新工具做任何你想做的事情。我在初学Emacs的时候，甚至用Emacs作为Web服务器开发了一款微信公众号小游戏（[开窗](https://github.com/redraiment/wechat.el)）。

不要给自己和工具打上标签，觉得自己只会做什么、不会做服么，觉得工具只能干什么、不能干什么。Emacs是能『玩』很久的玩具。

### 编辑器思维

因为Vim和Emacs都用了很多年，万物可编辑的思维给我的日常工作带来很多启发。

## 推荐环节

### Emacs Package

推荐大家熟练使用Emacs自带的键盘宏（Keyboard Macros，kmacro.el），不是所有效率的提升都需要写代码。

### 其他

如果你也是一名程序员，推荐阅读《计算机程序的构造和解释》（SICP）。
