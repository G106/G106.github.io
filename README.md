## Welcome to My GitHub Pages

You can use the [editor on GitHub](https://github.com/G106/G106.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# 以太坊
## solidty

# linux命令行三剑客
## grep
## awk
## sed

0311 编译原理 LLVM

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/G106/G106.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

# 0531
need to begin writing a blog everyday
LLVM IR是基于静态单赋值的, 并且提供了类型安全性,底层操作性,灵活性,因此能够清楚表达绝大多数高级语言.
# 0601
与优化器相似, LLVM代码生成器(code generator)也采用了模块的设计离你那, 它将代码生成问题分解为多个独立Pass: 指令选择,寄存器分配,指令调度,代码布局优化,代码发射. 同样, 也有许多内建的Pass, 它们默认执行, 但用户可以选择只执行其中一部分.
# 0615
抽象语法树（以下简称为AST） 是一门编程语言源码的抽象语法结构的树形表示。 各种语言组件， 例如表达式、 条件控制语句等， 都有相应的AST， 并被区分为操作符和操作数。 AST并不表示这些代码如何由语法生成， 而是表达了语言组件之间的关系。 AST忽略了一些无关紧要的元素， 例如标点符号、 定界符（通常是空格、 换行） 。 另外， AST中的每个元素都会有一些附加的属性， 在之后的编译阶段会有一定作用。例如， 源码行号信息就是这样一个属性， 在进行语法检查遇到语法错误时就可以输出错误代码的行号信息（在C++的Clang前端中， 位置、 行号、 列号等信息以及其他相关属性SourceManager类的一个对象存储） 。
