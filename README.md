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

### Markdown 常用转义字符
| 结果 | 描述 | 实体编号 | | 结果 | 描述 | 实体编号 | 
| --------- | ----------- |------------|---| --------- | ----------- |------------|
|       | space | &#38;&#35;32; |  |    [   | left square bracket | &#38;&#35;91; |
|    !   | exclamation mark | &#38;&#35;33; |  |    \   | backslash | &#38;&#35;92; |
|    "   | quotation mark | &#38;&#35;34; |  |    ]   | right square bracket | &#38;&#35;93; |
|    #   | number sign | &#38;&#35;35; |  |    ^   | caret | &#38;&#35;94; |
|    $   | dollar sign | &#38;&#35;36; |  |    _   | underscore | &#38;&#35;95; |
|    %   | percent sign | &#38;&#35;37; |  |    `   | grave accent | &#38;&#35;96; |
|    &   | ampersand | &#38;&#35;38; |  |    a   | lowercase a | &#38;&#35;97; | 
|    '   | apostrophe | &#38;&#35;39; |  |    b   | lowercase b | &#38;&#35;98; | 
|   （   | left parenthesis | &#38;&#35;40; |  |    c   | lowercase c | &#38;&#35;99; |
|    )   | right parenthesis | &#38;&#35;41; | |    d   | lowercase d | &#38;&#35;100; |
|    *   | asterisk | &#38;&#35;42; |  |    e   | lowercase e | &#38;&#35;101; |
|    +   | plus sign | &#38;&#35;43; |  |    f   | lowercase f | &#38;&#35;102; |
|    ,   | comma | &#38;&#35;44; |  |    g   | lowercase g | &#38;&#35;103; |
|    -   | hyphen | &#38;&#35;45; |  |    h   | lowercase h | &#38;&#35;104; |
|    -   | period | &#38;&#35;46; |  |    i   | lowercase i | &#38;&#35;105; |
|    /   | slash | &#38;&#35;47; |  |    j   | lowercase j | &#38;&#35;106; |
|    0   | digit0 | &#38;&#35;48; |  |    k   | lowercase k | &#38;&#35;107; |
|    1   | digit1 | &#38;&#35;49; |  |    l   | lowercase l | &#38;&#35;108; |
|    2   | digit2 | &#38;&#35;50; |  |    m   | lowercase m | &#38;&#35;109; |
|    3   | digit3 | &#38;&#35;51; |  |    n   | lowercase n | &#38;&#35;110; |
|    4   | digit4 | &#38;&#35;52; |  |    o   | lowercase o | &#38;&#35;111; |
|    5   | digit5 | &#38;&#35;53; |  |    p   | lowercase p | &#38;&#35;112; |
|    6   | digit6 | &#38;&#35;54; |  |    q   | lowercase q | &#38;&#35;113; |
|    7   | digit7 | &#38;&#35;55; |  |    r   | lowercase r | &#38;&#35;114; |
|    8   | digit8 | &#38;&#35;56; |  |    s   | lowercase s | &#38;&#35;115; |
|    9   | digit9 | &#38;&#35;57; |  |    t   | lowercase t | &#38;&#35;116; |
|    :   | colon | &#38;&#35;58; |  |    u   | lowercase u | &#38;&#35;117; |
|    ;   | semicolon | &#38;&#35;59; |  |    v   | lowercase v | &#38;&#35;118; |
|    <   | less-than | &#38;&#35;60; |  |    w   | lowercase w | &#38;&#35;119; |
|    =   | equals-to | &#38;&#35;61; |  |    x   | lowercase x | &#38;&#35;120; |
|    >   | greater-than | &#38;&#35;62; |  |    y   | lowercase y | &#38;&#35;121; |
|    ?   |question mark | &#38;&#35;63; |  |    z   | lowercase z | &#38;&#35;122; |
|    @   | at sign | &#38;&#35;64; |  |    {   | left curly brace | &#38;&#35;123; |
|    A   | uppercase A | &#38;&#35;65; |  |  &#124;|   vertical bar | &#38;&#35;124; |
|    B   | uppercase B | &#38;&#35;66; |  |     }  | right curly brace | &#38;&#35;125; |
|    C   | uppercase C | &#38;&#35;67; |  |     ~  | tilde | &#38;&#35;126; |
|    D   | uppercase D | &#38;&#35;68; |
|    E   | uppercase E | &#38;&#35;69; |
|    F   | uppercase F | &#38;&#35;70; |
|    G   | uppercase G | &#38;&#35;71; |
|    H   | uppercase H | &#38;&#35;72; |
|    I   | uppercase I | &#38;&#35;73; |
|    J   | uppercase J | &#38;&#35;74; |
|    K   | uppercase K | &#38;&#35;75; |
|    L   | uppercase L | &#38;&#35;76; |
|    M   | uppercase M | &#38;&#35;77; |
|    N   | uppercase N | &#38;&#35;78; |
|    O   | uppercase O | &#38;&#35;79; |
|    P   | uppercase P | &#38;&#35;80; |
|    Q   | uppercase Q | &#38;&#35;81; |
|    R   | uppercase R | &#38;&#35;82; |
|    S   | uppercase S | &#38;&#35;83; |
|    T   | uppercase T | &#38;&#35;84; |
|    U   | uppercase U | &#38;&#35;85; |
|    V   | uppercase V | &#38;&#35;86; |
|    W   | uppercase W | &#38;&#35;87; |
|    X   | uppercase X | &#38;&#35;88; |
|    Y   | uppercase Y | &#38;&#35;89; |
|    Z   | uppercase Z | &#38;&#35;90; |





### 2.MarkDown基本语法
#### 1) 标题
&#35; 一级标题     //对应html标签&#60;h1&#62;<br/>
&#35;&#35; 二级标题   //对应html标签&#60;h2&#62;<br/>
&#35;&#35;&#35; 三级标题 //对应html标签&#60;h3&#62;
