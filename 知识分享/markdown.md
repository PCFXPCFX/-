本文由Markdown编写
用于指导社团成员使用飞书

## Markdown是什么？

MD是一种极简主义的纯文本语法，文件以.md结尾

## 为什么要用markdown?

较于 Word, 兼容性非常高，且更为高效。

可以跨平台使用。

有许多网站都支持或正在使用 Markdown 语法。

可以使用Markdown记录笔记，做博客，胜任github等代码托管平台的readme.md等大部分文字工作

## 如何使用Markdown?

### pc端

- 网页：飞书，有道云笔记，坚果云等
- vscode + Markdown All in One
- 支持Markdown的笔记软件，如notion，印象笔记，有道云笔记
- marktext
- typora（收费软件，不建议付费）

### 安卓端

- 支持Markdown的笔记软件，如notion，印象笔记，有道云笔记，椒盐笔记等

### docker

- 思源笔记
- 为知笔记

## 简单语法

### 标题

使用#来创建不同字号，大小标题

```Markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

### 简单文字处理

```Markdown
*斜体文本*

**粗体文本**

***粗斜体文本***
此语法在飞书上有问题
```

*斜体文本* 

**粗体文本** 

***粗斜体文本***

 

### 分割线

```Markdown
***

---
```

### 删除线

```Markdown
~~删除内容~~
```

删除内容 

### 代码块

~~~Plain
``` 



```
~~~

### 链接

```Plain
[百度](https://baidu.com)
这个语法在飞书上不可用，但在大部分软件，和代码托管平台可用
```

飞书上直接 Ctrl+k实现

或者直接插入链接

![img](https://dcni0078teow.feishu.cn/space/api/box/stream/download/asynccode/?code=MGE5YjUyZjIxMzY1ODY3ODkxMDUwY2I0NGU5ZDY0M2ZfTXhJWDV1aXFTa0tJdHZoQW1kNno4ZkhQcFBpV1dHN2JfVG9rZW46RmNrbmJ0RmZ2b0EyM2h4dk5RZmNXcENhbnNoXzE3MzA4NjM5MDc6MTczMDg2NzUwN19WNA)

### 引用 

```Plain
> 这是引用
> 这也是引用
> 这还是引用
```

> 这是引用 这也是引用 这还是引用

### 无序列表 

```Plain
- 无序列表
* 无序列表
```

- 无序列表
- 无序列表

### 有序列表 

```Plain
1. 有序列表
2. 还是有序列表
    加了 ``` tab ```缩进一级
    继续
        继续缩进   
            继续
                还能再继续
                    无线缩进
```

1. 有序列表
2. 还是有序列表
   1. 加了 `Tab`缩进一级
   2. 继续
      1. 继续缩进
         1. 继续
            1. 还能在继续
               1. 无线继续

敲回车会自动补全, 敲回车后按下 `Tab` 会缩进一级. 

### 任务列表 

```Plain
TodoList:
[ ] 刷B站
[ ] 写代码
[x] 起床
[[ ] + 空格 ]
```

- 刷b站
- 写代码
- 起床

### 表格 

```Plain
| 学号 | 姓名  | 年龄 |
| :--- | :---: | ---: | (引号的位置代表着 左对齐, 居中, 右对齐)
|2024350143000|同学A|24|
|2024350143001|同学|25|
该语法有问题
建议直接插入表格
```

![img](https://dcni0078teow.feishu.cn/space/api/box/stream/download/asynccode/?code=NmUzYTUzNzI3MDEzN2NiNjZlMTIyMTk1Y2I0MzU1MWFfMTBtTEFLVVhxSG5TczdjMlljbTR4N2hwWENLMjROaDBfVG9rZW46Rnlab2JHQU1Db0ZpMXp4N0xtcmNKV2NIbmNsXzE3MzA4NjM5MDc6MTczMDg2NzUwN19WNA)

| 学号          | 姓名  | 年龄 |
| ------------- | ----- | ---- |
| 2024350143000 | 同学A | 24   |
| 2024350143001 | 同学  | 25   |
