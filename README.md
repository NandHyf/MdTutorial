# Markdown Tutorial

### LTS Project✅

### 🚧持续更新中

语法支持: Typora✅ VS Code✅

## 通用语法

- [分级标题](#分级标题)
- [有序列表](#有序列表)
- [无序列表](#无序列表)
- [加粗](#加粗)
- [斜体](#斜体)
- [删除线](#删除线)
- 引用
- 代码块
- 分割线
- 取消转义
- [嵌套使用](#嵌套使用)
- 链接
- [插入图片](#插入图片)
- [锚点](#锚点)
    - 锚点与\<a>标签
- 制表
    - 对齐

## 特殊语法

🚧受限于Markdown并非标准化的特性，以下语法的支持不具有普遍性，**请在使用前确认目标编辑器支持该特性**

- [高亮](#高亮)
- [上角标](#上角标)
- [下角标](#下角标)
- 下划线
- Markdown与HTML
    - \<a>
    - \<b>
    - \<i>
    - \<u>
    - \<hr>

## 快捷键

💡大部分Windows下的```Ctrl```对应于Mac OS中的```Command```

- [加粗](#加粗)
- [斜体](#斜体)
- [下划线](#下划线)
- [缩进与反缩进](#缩进与反缩进)

## 参考资料

- Markdown的历史
- 

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



### 无序列表

(三种方法)
``` markdown
- 某项
+ 某项
* 某项
```



### 加粗

(两种方法)

``` markdown
**待加粗文本**
__待加粗文本__
```



### 斜体

``` markdown
*待斜体文本*
```



### 删除线

```
~~待删除文本~~
```



### 嵌套使用



### 插入图片

``` markdown
![图裂掉时的备注文本](文件路径/文件名)
```

示例: 

```markdown
![Picture_a](C:/Users/root/Pictures/Saved Pictures/a.png)
```



💡文件路径支持相对路径的书写形式:

**同级目录下**

```markdown
![Pciture_a](/a.png)
```



### 锚点

``` markdown
[显示文本](#需要跳转到的标题)
```

💡标题这里更像是CSS语法，"#" 是锚点语法中的一部分，并不是Markdown中的"分级标题"语法, 因此不需要根据标题等级打出对应数量的"#"，只需要一个即可

示例: 

```markdown
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

**🚧锚点并不支持含有括号的标题，即便是英文半角也不受支持**，例如下标题: 

> ## 标题a(含括号内容)

如果写成: 

```markdown
[标题a](#标题a(含括号内容)) 
```

\>\>\> [标题a](#标题a(含括号内容))

明显可见识别内容将标题括号识别成了语法部分，因此即便渲染正确，却不一定能正确的链接和跳转



### 高亮

``` markdown
==待高亮文本==
```

**🚧高亮特性的支持并不具有普遍性，请在使用前确认编辑器的支持**



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

**🚧下角标特性的支持并不具有普遍性，请在使用前确认编辑器的支持**



### 加粗

``` markdown
Ctrl + B (Windows)
Command + B (Mac OS)
```



### 斜体

``` markdown
Ctrl + I (Windows)
Command + I (Mac OS)
```



### 下划线

```markdown
Ctrl + U (Windows)
Command + U (Mac OS)
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
