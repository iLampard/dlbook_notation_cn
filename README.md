# dlbook_notation_cn

[Deep Learning](www.deeplearningbook.org) 的[tex源码](https://github.com/goodfeli/dlbook_notation)已经开源。 本项目在其源码上稍加修改，使其更适合中文环境。

## 主要修改

- *notation_example.tex* 中增加了ctex包的引用，调整了字体大小以及行间距（比原版更紧凑一些）
- *notation.tex* 将符号表都翻译成了中文
- *math_commands.tex* 中把章节、公式、算法等引用的返回值改成对应的中文，如“公式(1.1)， 算法2.3，第3章”等 

作为示例，在*notation_example.tex*中添加了一个中文段落，*notation.bib*中添加了一行中文文献引用。效果见下文截屏。

## 如何编译

仅尝试过在VSCode上编译，其他方式尚不确定。
- 编辑器： VSCode 1.81 
- 集成环境： TexLive 2017 
- 插件：Latex Workshop，使用默认设置(latexmk)



![](/png/title.png)

![](/png/notation.png)

![](/png/content.png)

![](/png/section_logistic.png)

![](/png/figure.png)

![](/png/ref.png)