
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



```flow
st=>start: Start|past:>http://www.google.com[blank]
e=>end: End:>http://www.google.com
op1=>operation: My Operation|past
op2=>operation: Stuff|current
sub1=>subroutine: My Subroutine|invalid
cond=>condition: Yes
or No?|approved:>http://www.google.com
c2=>condition: Good idea|rejected
io=>inputoutput: catch something...|request

st->op1(right)->cond
cond(yes, right)->c2
cond(no)->sub1(left)->op1
c2(yes)->io->e
c2(no)->op2->e
```


```sequence
A->>B: 你好
Note left of A: 我在左边     // 注释方向，只有左右，没有上下
Note right of B: 我在右边
B-->A: 很高兴认识你
```