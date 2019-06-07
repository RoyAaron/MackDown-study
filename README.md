# MackDown-study

## 一、MarkDown简介及其基本语法
### 1、MarkDown简介
Markdown 是一种轻量级的「标记语言」，它的优点很多，目前也被越来越多的写作爱好者，撰稿者广泛使用。看到这里请不要被「标记」、「语言」所迷惑，Markdown 的语法十分简单。常用的标记符号也不超过十个，这种相对于更为复杂的 HTML 标记语言来说，Markdown 可谓是十分轻量的，学习成本也不需要太多，且一旦熟悉这种语法规则，会有一劳永逸的效果。

　   用markdown编写完后，我们可以导出到html发布到网站或者导出pdf保存到本地，十分的方便。最重要的是markdown源文件是纯文本文件，也就是意味着可以跨平台，使用 Markdown 的优点如下：
* 专注你的文字内容而不是排版样式，安心写作。
* 轻松的导出 HTML、PDF 和本身的 .md 文件。
* 纯文本内容，兼容所有的文本编辑器与字处理软件。
* 随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。
* 可读、直观、学习成本低。

这里先给大家推荐一款我最喜欢的MarkDown在线编辑器，CmdMarkDown,网址为：https://www.zybuluo.com/mdeditor，大家可以先在这里学习基本语法。


### 2.MarkDown基本语法
#### 1) 标题
&#35; 一级标题       //对应html标签&#60;h1&#62;   
&#35;&#35; 二级标题     //对应html标签&#60;h2&#62;   
&#35;&#35;&#35; 三级标题   //对应html标签&#60;h3&#62;

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。
这里要注意的是#和后面的内容之间要有空格隔开。

#### 2)粗体和斜体
用两个 * 包含一段文本就是粗体的语法，用一个 * 包含一段文本就是斜体的语法。

*MarkDown*     // 斜体   
**MarkDown**  // 粗体    


#### 3)分割线
 &#45;&#45;&#45;  或  &#42;&#42;&#42;
 
---
***

#### 4) 列表
这里的列表指的就是我们html中常用的有序列表和无序列表，及&#60;ul&#62;和&#60;ol&#62;   
&#42; 1  或者 - 1  或者 + 1   
&#42; 2  或者 - 2  或者 + 2     
&#42; 3  或者 - 3  或者 + 3 

这里要注意的是有使用&#42;就都是用&#42;号，使用 '&#45;' 就都用 '&#45;' 号，混合使用会出错的。**还有就是&#42;和内容之间要加一个空格**。

有序列表比较简单，写法如下：  
1.items1  
2.items2
2.items3


#### 5）引用
如果你需要引用一小段别处的句子，那么就要用引用的格式。引用的语法就是在文字前面加 &#62; ,如：  
&#62; 这里是引用:  
输出如下：  
> 这里是引用  

**注：** 不同的markdown编辑器输出的显示略有不同.

#### 6) 超链接
超链接的写法比较特殊，但是也很好记忆，如我们加一个百度的超链接，markdown语法如下：  
&#91;百度&#93;(http://www.baidu.com) [百度](http://www.baidu.com)  
当我们导出到html中时，就会得到一个<a>标签的输出。    

如果我们要加入一张图片，其语法如下：  
&#33;&#91;百度&#93;(http://www.baidu.com)  
![百度](http://www.baidu.com/img/bdlogo.png)  


#### 7) 表格
markdown的表格我感觉写起来并不是那么简便，我们先来看一下表格的写法：  
| Tables        | Are           | Cool  |  
| ------------- |:-------------:| -----:|  
| col 3 is      | right-aligned | $1600 |  
| col 2 is      | centered      |   $12 |  
| zebra stripes | are neat      |    $1 |  

显示结果如下：  

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

**注:** 这里值得注意的是第二行，|:------------:|,这里两边加冒号就是居中，如果只有一边加冒号就是哪边对齐，如Cool那一列就是右对齐。默认左对齐。

#### 8) 代码框
程序员写东西，难免会插入一些代码，在 Markdown下实现也非常简单，只需要用两个 ` 把中间的代码包裹起来，代码的语法如下：

· -- 代码内容-- ·

`-- module.exports = {
  plugins: {
    autoprefixer: {},
    'postcss-px2rem': {
      remUnit: 37.5
    }
  }
} --`

`--module.exports = {
  plugins: {
    autoprefixer: {},
    'postcss-px2rem': {
      remUnit: 37.5
    }
  }
}--`

 注意这里的`不是单引号，而是键盘左边那个~上的`。




### Markdown 常用转义字符
| 结果 | 描述 | 实体编号 | | 结果 | 描述 | 实体编号 | 
|:---:|---|:---:|---|:---:|---|:---:|
|    &#32;   | space | &#38;&#35;32; |  |    &#80;   | uppercase P | &#38;&#35;80; |
|    &#33;   | exclamation mark | &#38;&#35;33; |  |    &#81;   | uppercase Q | &#38;&#35;81; |
|    &#34;   | quotation mark | &#38;&#35;34; |  |    &#82;   | uppercase R | &#38;&#35;82; |
|    &#35;   | number sign | &#38;&#35;35; |  |   &#83;   | uppercase S | &#38;&#35;83; |
|    &#36;   | dollar sign | &#38;&#35;36; |  |    &#84;   | uppercase T | &#38;&#35;84; |
|    &#37;   | percent sign | &#38;&#35;37; |  |    &#85;   | uppercase U | &#38;&#35;85; |
|    &#38;   | ampersand | &#38;&#35;38; |  |    &#86;   | uppercase V | &#38;&#35;86; |
|    &#39;   | apostrophe | &#38;&#35;39; |  |    &#87;   | uppercase W | &#38;&#35;87; |
|    &#40;   | left parenthesis | &#38;&#35;40; |  |    &#88;   | uppercase X | &#38;&#35;88; |
|    &#41;   | right parenthesis | &#38;&#35;41; |  |    &#89;   | uppercase Y | &#38;&#35;89; |
|    &#42;   | asterisk | &#38;&#35;42; |  |    &#90;   | uppercase Z | &#38;&#35;90; |
|    &#43;   | plus sign | &#38;&#35;43; |  |    &#91;   | left square bracket | &#38;&#35;91; |
|    &#44;   | comma | &#38;&#35;44; |  |    &#92;   | backslash | &#38;&#35;92; |
|    &#45;   | hyphen | &#38;&#35;45; |  |    &#93;   | right square bracket | &#38;&#35;93; |
|    &#46;   | period | &#38;&#35;46; |  |    &#94;   | caret | &#38;&#35;94; |
|    &#47;   | slash | &#38;&#35;47; |  |    &#95;   | underscore | &#38;&#35;95; |
|    &#48;   | digit0 | &#38;&#35;48; |  |    &#96;   | grave accent | &#38;&#35;96; |
|    &#49;   | digit1 | &#38;&#35;49; |  |    &#97;   | lowercase a | &#38;&#35;97; | 
|    &#50;   | digit2 | &#38;&#35;50; |  |    &#98;   | lowercase b | &#38;&#35;98; | 
|    &#51;   | digit3 | &#38;&#35;51; |  |    &#99;   | lowercase c | &#38;&#35;99; |
|    &#52;   | digit4 | &#38;&#35;52; |  |    &#100;   | lowercase d | &#38;&#35;100; |
|    &#53;   | digit5 | &#38;&#35;53; |  |    &#101;   | lowercase e | &#38;&#35;101; |
|    &#54;   | digit6 | &#38;&#35;54; |  |    &#102;   | lowercase f | &#38;&#35;102; |
|    &#55;   | digit7 | &#38;&#35;55; |  |    &#103;   | lowercase g | &#38;&#35;103; |
|    &#56;   | digit8 | &#38;&#35;56; |  |    &#104;   | lowercase h | &#38;&#35;104; |
|    &#57;   | digit9 | &#38;&#35;57; |  |    &#105;   | lowercase i | &#38;&#35;105; |
|    &#58;   | colon | &#38;&#35;58; |  |    &#106;   | lowercase j | &#38;&#35;106; |
|    &#59;   | semicolon | &#38;&#35;59; |  |    &#107;   | lowercase k | &#38;&#35;107; |
|    &#60;   | less-than | &#38;&#35;60; |  |    &#108;   | lowercase l | &#38;&#35;108; |
|    &#61;   | equals-to | &#38;&#35;61; |  |    &#109;   | lowercase m | &#38;&#35;109; |
|    &#62;   | greater-than | &#38;&#35;62; |  |    &#110;   | lowercase n | &#38;&#35;110; |
|    &#63;   |question mark | &#38;&#35;63; |  |    &#111;   | lowercase o | &#38;&#35;111; |
|    &#64;   | at sign | &#38;&#35;64; |  |    &#112;   | lowercase p | &#38;&#35;112; |
|    &#65;   | uppercase A | &#38;&#35;65; |  |    &#113;   | lowercase q | &#38;&#35;113; |
|    &#66;   | uppercase B | &#38;&#35;66; |  |    &#114;   | lowercase r | &#38;&#35;114; |
|    &#67;   | uppercase C | &#38;&#35;67; |  |    &#115;   | lowercase s | &#38;&#35;115; |  
|    &#68;   | uppercase D | &#38;&#35;68; |  |    &#116;   | lowercase t | &#38;&#35;116; |
|    &#69;   | uppercase E | &#38;&#35;69; |  |    &#117;   | lowercase u | &#38;&#35;117; |
|    &#70;   | uppercase F | &#38;&#35;70; |  |    &#118;   | lowercase v | &#38;&#35;118; |
|    &#71;   | uppercase G | &#38;&#35;71; |  |    &#119;   | lowercase w | &#38;&#35;119; |
|    &#72;   | uppercase H | &#38;&#35;72; |  |    &#120;   | lowercase x | &#38;&#35;120; |
|    &#73;   | uppercase I | &#38;&#35;73; |  |    &#121;   | lowercase y | &#38;&#35;121; |  
|    &#74;   | uppercase J | &#38;&#35;74; |  |    &#122;   | lowercase z | &#38;&#35;122; |
|    &#75;   | uppercase K | &#38;&#35;75; |  |    &#123;   | left curly brace | &#38;&#35;123; |
|    &#76;   | uppercase L | &#38;&#35;76; |  |    &#124;   |   vertical bar | &#38;&#35;124; |
|    &#77;   | uppercase M | &#38;&#35;77; |  |    &#125;   | right curly brace | &#38;&#35;125; |
|    &#78;   | uppercase N | &#38;&#35;78; |  |    &#126;   | tilde | &#38;&#35;126; |
|    &#79;   | uppercase O | &#38;&#35;79; |


 
#### 设备控制 ASCII代码
| 结果 | 描述 | 实体编号 | | 结果 | 描述 | 实体编号 | 
|:----:| ----------- |:-----:|---|:----:| ------- |:-----:|
|  NUL  |	null character   |  &#38;&#35;00;  |  |    DC1  |	device control 1  |	&#38;&#35;17; |
|  SOH  |	start of header   |  &#38;&#35;01;   |  |  DC2  |	device control 2  |	&#38;&#35;18;  |
|  STX  |	start of tex   |  &#38;&#35;02;   |  |  DC3  |	device control 3  |	&#38;&#35;19;  |
|  ETX  |	end of tex   |  &#38;&#35;03;   |  |  DC4  |	device control 4  |	&#38;&#35;20;  |
|  EOT  |	end of transmission   |  &#38;&#35;04;   |  |  NAK  |	negative acknowledge  |	&#38;&#35;21;  |
|  ENQ  |	enquiry   |  &#38;&#35;05;   |  |  SYN  |	synchronize	| &#38;&#35;22  |
|  ACK  |	acknowledge   |  &#38;&#35;06;   |  |  ETB  |	end transmission block  |	&#38;&#35;23;  |
|  BEL  |	bell (ring)   |  &#38;&#35;07;   |  |  CAN  |	cancel   | &#38;&#35;24;  |
|  BS |   backspace   | &#38;&#35;08   |  |  EM  |	end of medium  |	&#38;&#35;25;  |
|  HT |   horizontal tab   |  &#38;&#35;09;   |  |  SUB  |	substitute  |	&#38;&#35;26;  |
|  LF |   line feed   |  &#38;&#35;10;   |  |  ESC  |	escape  |	&#38;&#35;27;  |
|  VT |   vertical tab   |  &#38;&#35;11;   |  |  FS |	file separator  |	&#38;&#35;28;  |
|  FF |   form feed   |  &#38;&#35;12;   |  |  GS  |	group separator  |	&#38;&#35;29;  |
|  CR |   carriage return   |  &#38;&#35;13;   |  |  RS  |	record separator  |	&#38;&#35;30;  |
|  SO |   shift out   |  &#38;&#35;14;   |  |  US  |	unit separator  |	&#38;&#35;31;  |
|  SI |   shift in   |  &#38;&#35;15;   |  |  DEL  |	delete (rubout)  |	&#38;&#35;127;  |
|  DLE  |	data link escape   |  &#38;&#35;16;   |  |

