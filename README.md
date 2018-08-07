# HTML和MARKDOWN 语法和效果的对比

---------------

### html表格
PS:不能把border显示出来，表格内填充什么的都没有效果。标题也没有居中，这部分和HTML大有不同。
<table border="0" cellpadding="10" style="text-align:center;">
  <caption>勾股表格</caption>
  <tr>
    <th>x</th>
    <th>y</th>
    <th>z</th>
  </tr>
  <tr>
    <td>3</td>
    <td>4</td>
    <td>5</td>
  </tr>
</table>

### Markdown表格

x|y|z
:--:|:--:|:--:
3|4|5

--------------------

<h1>标题一<h1>
<h2>标题二<h2>
<h3>标题三<h3>
<h4>标题四<h4>
<h5>标题五<h5>
<h6>标题六<h6>

# 标题一

-------------------

### html字体效果

**颜色属性都不起作用**
<p style="background-color:purple">柳梦璃</p>

<del>删除字效果</del>

<ins>下划线效果</ins>

<i>斜体</i>

<big>big标签</big>

<small>small标签</small>

<p>这是<sub>下标</sub>。</p>

<p>这是<sup>上标</sup>。</p>

-----------------------

### html缩写
**缩写的两种写法都不起作用**
<abbr title="World Health Organization">WHO</abbr><br>
<dfn title="World Health Organization">WHO</dfn><br>

------------------------

### markdown字体效果

*Markdown斜体*

<b>粗体</b>
<strong>强调</strong>

**Markdown强调**

-----------------------------

### 链接
由下面的例子可以看到，实际上使用target="\_blank"的写法没有效果。**无法在新页面实现跳转**。以此看来，在这个地方还是markdown的写法为主流。  
[柳梦璃](https://baike.baidu.com/item/柳梦璃/3622691?fr=aladdin)  
<a href="https://baike.baidu.com/item/柳梦璃/3622691?fr=aladdin" target="_blank">柳梦璃</a>  

---------------------------

### Markdown引用
>柳梦璃，单机游戏《仙剑奇侠传四》第二女主角。
>幻瞑界主人婵幽之女。十九年前，在妖界与琼华派大战中受到重伤，被云天青救下后交由寿阳县令柳世封夫妇收养。后结识云天河、韩菱纱，并辗转拜入琼华派，逐渐发现了自己的身世。 [1] 

<h3>HTML引用</h3>
<blockquote>
  柳梦璃，单机游戏《仙剑奇侠传四》第二女主角。
  幻瞑界主人婵幽之女。十九年前，在妖界与琼华派大战中受到重伤，被云天青救下后交由寿阳县令柳世封夫妇收养。后结识云天河、韩菱纱，并辗转拜入琼华派，逐渐发现了自己的身世。 [1] 
</blockquote>

<hr>

### html地址
<strong>address标签不起作用。</strong>
<address>
  Written by Zhang<br>
  Visit us at example.com<br>
  Sydney Australia<br>
</address>
