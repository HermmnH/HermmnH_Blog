
## 基于决策树的分类
系列内容为自己学习数据挖掘的一个笔记
本部分内容来源《数据挖掘导论》4.3节

### 决策树生成算法
所谓决策树，就是一个类似于流程图的树形结构，树内部的每一个节点代表的是对一个属性的测试，树的分支代表该属性的每一个测试结果，而树的每一个叶子节点代表一个类别。树的最高层是就是根节点。下图即为一个决策树的示意描述，内部节点用矩形表示，叶子节点用椭圆表示（但是这里因为文本编辑的原因，内部节点用菱形表示）。该决策树用于对一个顾客是否会在本商场购买电脑进行分类预测。

'''flow
e1=>end: YES
op11=>operation: 年龄？
op21=>operation: 学生？
op22=>operation: 信用等级？
op11(<30)->op21
op11(30-40)->e1
op11(>40)->op22
e211=>end: YES
e212=>end: NO
op21(是)->e211
op21(否)->e212
e221=>end: YES
e222=>end: NO
op22(一般)->e221
op22(良好)->e222
'''


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/HermmnH/HermmnH_Blog/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<a href="https://www.codecogs.com/eqnedit.php?latex=ax^{2}&space;&plus;&space;by^{2}&space;&plus;&space;c&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/png.latex?ax^{2}&space;&plus;&space;by^{2}&space;&plus;&space;c&space;=&space;0" title="ax^{2} + by^{2} + c = 0" /></a>
