# Markdown Tutorial

### ✅LTS！

### 🚧持续更新！

### 欢迎加急⚡

## 通用语法

- [分级标题](#分级标题)
- [有序列表](#有序列表)
- [无序列表](#无序列表)
- [加粗](#加粗)
- [斜体](#斜体)
- [删除线](#删除线)
- [插入图片](#插入图片)
- [锚点](#锚点)

## 特殊语法

- [高亮](#高亮)
- [上角标](#上角标)
- [下角标](#下角标)

## 快捷键

- [加粗](#加粗)

- [斜体](#斜体)

- [缩进与反缩进](#缩进与反缩进)

### 分级标题

``` markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```




### 有序列表

```markdown
1. 第一项
2. 第二项
3. 第二项
```



### 无序列表(三种方法)

``` markdown
1. - 某项
2. + 某项
3. *某项
```

💡推荐使用"- ", 方便快捷



### 加粗

``` markdown
**待加粗文本**
```



### 斜体

``` markdown
*待斜体文本*
```



### 删除线

> \~\~待删除文本\~\~ 



### 插入图片

``` markdown
![文件名](文件路径/文件名)
```

💡



### 锚点

``` markdown
[显示文本](#需要跳转到的标题)
```

💡标题这里更像是CSS语法，"#" 是锚点语法中的一部分，并不是Markdown中的"分级标题"语法, 因此不需要根据标题等级打出对应数量的"#"，只需要一个即可

例如:

``` markdown
[说明文档](#Readme)

...(中间段落)

## Readme

```

会被渲染为: 

> [说明文档](#Readme)   /\*可以看到链接标题的"(#Readme)"是不会被渲染的*/
>
> 
>
> ...(中间段落)
>
> 
>
> ## Readme
>
> 



### 高亮

``` markdown
==待高亮文本==
```



### 上角标

``` markdown
需要上角标的字符^2^
```

💡"2"处可以是任意字符

渲染实例:

``` markdown
10^2^
```

\>\>\> 10^2^



### 下角标

``` markdown
需要上角标的字符~2~
```

💡"2"处可以是任意字符

渲染实例:

``` markdown
H~2~O
```

\>\>\> H~2~O



### 加粗

``` markdown
Ctrl + B
```



### 斜体

``` markdown
Ctrl + I
```



### 缩进与反缩进

**缩进:**

```markdown
Tab
```

**反缩进(两种方法):**

``` markdown
1. Backspace
2. Shift + Tab
```

