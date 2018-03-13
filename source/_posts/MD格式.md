
---
title: MD格式
---

# h1
## h2
### h3
#### h4
##### h5
###### h6

一级标题
======================

大法师打发的说法


二级标题
---------------------

> hello world!

> hello world!
hello world!
hello world!  

[百度一下](https://www.baidu.com/)


|    a    |       b       |      c     |
|:-------:|:------------- | ----------:|
|   居中  |     左对齐    |   右对齐   |
|=========|===============|============|

<p style="color: #AD5D0F;font-size: 30px; font-family: '宋体';">内联样式</p>


<pre>
hello world 
         hi
  hello world 
</pre>

```
<div>   
    <div></div>
    <div></div>
    <div></div>
</div>
```
$$ x \href{why-equal.html}{=} y^2 + 1 $$

$ x = {-b \pm \sqrt{b^2-4ac} \over 2a}. $

***
---
* * *



```flow                     // 流程
st=>start: 开始|past:> http://www.baidu.com // 开始
e=>end: 结束              // 结束
c1=>condition: 条件1:>http://www.baidu.com[_parent]   // 判断条件
c2=>condition: 条件2      // 判断条件
c3=>condition: 条件3      // 判断条件
io=>inputoutput: 输出     // 输出
//----------------以上为定义参数-------------------------

//----------------以下为连接参数-------------------------
// 开始->判断条件1为no->判断条件2为no->判断条件3为no->输出->结束
st->c1(yes,right)->c2(yes,right)->c3(yes,right)->io->e
c1(no)->e                   // 条件1不满足->结束
c2(no)->e                   // 条件2不满足->结束
c3(no)->e                   // 条件3不满足->结束
```


```sequence
A->>B: 你好
Note left of A: 我在左边     // 注释方向，只有左右，没有上下
Note right of B: 我在右边
B-->A: 很高兴认识你
```