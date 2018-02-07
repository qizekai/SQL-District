###    一、利用Markdown可以做什么？

#### 1.代码高亮
```php 
<?php 
    echo "hello World";
```
    <?php
        echo 'hello World';
    
#### 2.制作待办事项To-do List
- [x] 已经完成项目
     - [x] 已经完成项目2
     - [x] 已经完成项目2
- [ ] 代办事项1
- [ ] 代办事项2

#### 3. 高效绘制 流程图、序列图、甘特图、表格
##### 3.1 流程图
```
graph TD
    A[Christmas] --> B(go Shopping)
    B-->C(let's me to think)
    C -->|one| D(think) 
    C -->|two| E[think is]
    C -->|three| F[do car]
```
##### 3.2 序列图

```
sequenceDiagram
    loop everyday
        Alice-->>John:Hello john,how are you
        John-->>Alice:Great!
    end
```

##### 3.2 甘特图
```
gantt
dateFormat YYYY-MM-DD
title 产品计划表
section 初期阶段
明确需求: 20160-03-01,10d
section 中期阶段
跟进开发: 2016-03-11,15d
section 后期阶段
走差测试: 2016-03-20,9d
```
##### 3.3 表格

header 1 | header 2 | header 3
---|---|---
row 1 col 1 | row 1 col 2 | row 1 col 2
row 2 col 1 | row 2 col 2 | row 2 col 2

##### 3.4 书写数学公式

## Mathematical formula `$y = x^2$`
Inline math: 
`$\dfrac{ \frac{1}{2}[1-(\tfrac{1}{2})^n] }{ 1-\tfrac{1}{2} }=S_n$`

#### 4.标题
# # 一级标题
## ## 二级标题
### ### 三级标题
#### #### 四级标题

#### 5.列表
#### 无序列表 
- 列表1
    - 列表 1.1
    - 列表 1.2
- 列表2
- 列表3

* 列表1
    * 列表 1.1
    * 列表 1.2
* 列表2
* 列表3

+ 列表1
    + 列表 1.1
    + 列表 1.2
+ 列表2
+ 列表3
 
#### 有序列表
1. 列表1
    1. 列表1.1
    2. 列表1.3
2. 列表2
3. 列表3

#### 6.引用
###### 引用
> 记录,成为更好的自己。 --有道云笔记

#### 7.粗体和斜体
*这是斜体*

**这是粗体**

#### 8.链接和图片
#### 插入链接
[有道云笔记官网](http://youdaoyun.com)
[markdown语法](https://www.appinn.com/markdown/)
#### 插入图片
![有道云笔记官网](http://tb.himg.baidu.com/sys/portrait/item/1043e69c89e98193e4ba91e7ac94e8aeb0e5b08fe7bc965e56)
###### 注：插入图片的语法和链接的语法很像，只是前面多了一个 ！

#### 9.分割线

这是第一段内容
***
这是第二段内容
---
这是第三段
___
这是第四段
###### 注意:用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格

#### 10.表格

header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2

