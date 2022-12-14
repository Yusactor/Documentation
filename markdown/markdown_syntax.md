# Markdown语法

### 1.标题

`#`一级标题
`##`二级标题
以此类推</br>
在目录中会分级显示出来

### 2.字体

**加粗**：`**加粗**`或者 `__加粗__` </br>
加粗的快捷键是`Ctrl+B` 

*斜体*：`*斜体*`或者`_斜体_` </br>
斜体的快捷键是`Ctrl+I`

***斜体加粗***：`***斜体加粗***` </br>

~~删除线~~：`~~删除线~~`
### 3.引用

> 引用：`>引用`

> > 引用：`>>引用`

### 4.分割线

---

----

***

****

```
---
----
***
****
这四种都可以
```

### 5.图片

格式：`![图片描述](图片地址 "图片标题")`
![图片描述](.\鲨鱼.jpg "鲨鱼")

### 6.超链接

`[超链接名](超链接地址 "超链接title")`
[bilibili](www.bilibili.com)

### 7.列表

#### 7.1无序列表

- 列表内容

```
- 列表内容
+ 列表内容
* 列表内容
```

#### 7.2 有序列表

1. 列表内容
2. 列表内容
3. 列表内容

```
1.列表内容
2.列表内容
3.列表内容
注：输入完序号之后要接一个空格
```

### 8.表格

| 表头   | 表头   |
| ------ | ------ |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

```
|  表头   | 表头  |
|  ----  | ----  |
| 单元格  | 单元格 |
| 单元格  | 单元格 |
```

- **-:** 设置内容和标题栏居右对齐。
- **:-** 设置内容和标题栏居左对齐。
- **:-:** 设置内容和标题栏居中对齐。

| 左对齐 | 右对齐 | 居中对齐 |
| :----- | -----: | :------: |
| 单元格 | 单元格 |  单元格  |
| 单元格 | 单元格 |  单元格  |

```
| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 单元格 | 单元格 | 单元格 |
| 单元格 | 单元格 | 单元格 |
```

### 9.代码

`代码内容`

```
`代码内容`
```

```
​```代码块```
```
如果要标记代码块的语言类型,需要用四个点:
````Java
String this="java";
````
### 10.流程图
Markdown可以绘制流程图
通过` ```flow `创建

### 11.自动生成目录
右键选择Command Palette 并输入</br>
`>Create Table of Contents`
- [Markdown语法](#markdown语法)
    - [1.标题](#1标题)
    - [2.字体](#2字体)
    - [3.引用](#3引用)
    - [4.分割线](#4分割线)
    - [5.图片](#5图片)
    - [6.超链接](#6超链接)
    - [7.列表](#7列表)
      - [7.1无序列表](#71无序列表)
      - [7.2 有序列表](#72-有序列表)
    - [8.表格](#8表格)
    - [9.代码](#9代码)
    - [10.流程图](#10流程图)
    - [11.自动生成目录](#11自动生成目录)
    - [12.内联html代码](#12内联html代码)
    - [13.内嵌LATEX公式](#13内嵌latex公式)
    - [14.图床](#14图床)

### 12.内联html代码
直接输入html代码就可以
<div>
    <font style='color:green'>这是蓝色</font>
</div>

### 13.内嵌LATEX公式
使用dollar符包裹
$\LaTeX$：`$\LaTeX$`
$a^2+b=c^3$:`$a^2+b=c^3$`

Latex块用$$包裹:(就像代码块一样)
```
$$
{Latex代码}
$$
```

### 14.图床