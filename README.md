# Gitbook-example

本文介绍使用gitbook制作[**Perl-Programming-experience**](https://github.com/gwlwmm/Perl-Programming-experience)文档并将其发布到个人网站的详细过程。

---

## 工具准备

### 安装gitbook editor

下载地址：[https://legacy.gitbook.com/editor](https://legacy.gitbook.com/editor)

### 安装git客户端

下载地址：[https://git-scm.com/download/win](https://git-scm.com/download/win)

### 安装nodejs

下载地址：[https://nodejs.org/zh-cn/](https://nodejs.org/zh-cn/)

### 安装gitbook-cli

打开cmd命令行窗口，输入

```
npm install gitbook-cli -g
```

### 安装calibre-ebook

下载地址：[https://calibre-ebook.com/download\_windows](https://calibre-ebook.com/download_windows)

---

## 编写文档

### 构建git项目

* 在git操作新建项目，命名为：Perl-Programming-experience

本文在github建立的项目为：[https://github.com/gwlwmm/Perl-Programming-experience](https://github.com/gwlwmm/Perl-Programming-experience)

有关git操作，请另搜资料。

* 新建项目后，初始化新建README.md（任意内容）

### 本地下载git项目

* 在git上，为当前windows系统添加ssh key

详细操作，请另搜资料。

* 在windows打开一个目录，本例为E:\mydata\coderlikewind\perl

* 单击鼠标右键-------&gt;Git Bash Here

* 下载代码

在git bash窗口执行

```
git clone git@github.com:gwlwmm/Perl-Programming-experience.git
```

### 使用gitbook editor编辑文档

* 打开gitbook editor

* 选择菜单---&gt;GitBook Editor----&gt;open

![](/assets/gitbook-editor-open.png)

* 选择E:\mydata\coderlikewind\perl\Perl-Programming-experience

![](/assets/gitbook-editor-open2.png)

* 编辑文档内容，本例文档内容如下

![](/assets/gitbook-editor-content.png)

编写文档几点建议：

1. 目录结构就是书籍的目录结构，因此要仔细严谨的命名，错误后再来修改是比较麻烦的。
2. 如对目录项序号没有要求，无需为目录结构编写序号，可以在发布文档时自动生成。
3. 编写文章内容时，具有层次结构，Paragraph从Heading1开始
4. 保存文档时，如果提示文件有改动，请勿理会，稍等一会儿，这个是软件有问题。如果点击任何按钮，可能导致改动丢失。
5. 编辑器会修改git状态，并且会检查目录下的文件改动。例如，在目录下直接增加a.md，打开编辑器时，会提示新增文件，此时选择sync，则会修改git 状态，类似git add a.md; 而如果选择discard，则a.md会被删除。所以，如果想不通过编辑器修改项目文件，请不要打开编辑器。
6. 编写文档时，各种排版功能，请自行试验。



---

## 参考资料

[https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md)

[https://github.com/GitbookIO/gitbook](https://github.com/GitbookIO/gitbook)

[https://toolchain.gitbook.com/](https://toolchain.gitbook.com/)

