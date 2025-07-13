# Markdown简易语法

一些简单的Markdown语法，方便后续技术博客编辑。通过简易学习，后续可按需自行探索进阶内容。

## 1 标题

使用 `#`，表示1-6级标题。

> \# 一级标题
> \## 二级标题
> \### 三级标题
> \#### 四级标题
> \##### 五级标题
> \###### 六级标题

效果：

> # 一级标题
>
> ## 二级标题
>
> ### 三级标题
>
> #### 四级标题
>
> ##### 五级标题
>
> ###### 六级标题

## 2 段落

直接换行即可（**ENTER**键）

## 3 引用

在段落的每行或者只在第一行使用符号 `>`,还可使用多个嵌套引用，如：

> \> 引用
> \>> 嵌套引用

效果：

> 引用
>
>> 嵌套引用
>>

## 4 代码区块

代码区块的建立是在每行加上4个空格或者一个制表符（**TAB键**）。如
普通段落：

void main()
{
    printf("Hello, Markdown.");
}

代码区块：

    void main()
    {
        printf("Hello, Markdown.");
    }

## 5 强调

在强调内容两侧分别加上 `*`，如：

> \*斜体\*
> \*\*粗体\*\*

效果：

> *斜体*
> **粗体**

## 6 列表

使用 `*`标记无序列表，如：

> \* 第一项
> \* 第二项
> \* 第三项

效果：

* 1
* * 2.1
  * 2.2
* 3
  有序列表的标记方式是将上述的符号换成数字,并辅以 `.`，如：

> 1 . 第一项
> 2 . 第二项
> 3 . 第三项

效果：

> 1. 第一项
> 2. 第二项
> 3. 第三项

## 7 分割线

分割线使用三个或以上 `*`。

---

分割线

---

## 8 链接

目的链接

https://github.com/hexiruwu/Markdown-Simple-grammar

链接可以由两种形式生成：

1.**行内式**：

> [Markdown简易语法](https://github.com/hexiruwu/Markdown-Simple-grammar "Markdown")。

2.**参考式**：

> [Markdown简易语法][1]

[1]: https://github.com/hexiruwu/Markdown-Simple-grammar
## 9 图片

添加图片的形式和链接相似，只需在链接的基础上前方加一个 `！`。
![shadow](https://github.com/hexiruwu/Markdown-Simple-grammar/blob/main/sorce/shadow.jpg)

## 10 反转义 `\`

\*

## 11 标记 

起标记作用。如：

> \`ctrl+a\`

效果：

> `ctrl+a`

参考学习链接：
[MARKDOWN 中文](https://www.markdown.cn/)
[Markdown 表格生成器](https://www.tablesgenerator.com/markdown_tables)
[Markdown 基本语法](https://github.com/younghz/Markdown) 
