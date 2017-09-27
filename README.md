Practical python and opencv中译本

说明：2014年8月份开的一个坑，只翻译到第四章，没想到压在箱子底下我都快忘了的时候，被翻出来了，看来这开得坑还得继续填，o(╯□╰)o。

### 模板在OS X下配置

本书模板在windows下按作者给的说明来配置即可，如果是在OS X下，安装完相关的字体后，把elegantbooks.cls中的下面部分出现的"微软雅黑"替换成英文表示“Microsoft YaHei”即可(我自己的替换如下了)

```latex
\setCJKmainfont[BoldFont={Microsoft YaHei},ItalicFont={Microsoft YaHei}]{Microsoft YaHei}%方正书宋_GBK Adobe Song Std L
\setCJKsansfont[BoldFont={Microsoft YaHei}]{Microsoft YaHei}
%\setCJKmonofont{方正中等线简体}
\setCJKmonofont{Microsoft YaHei}
\XeTeXlinebreaklocale "zh"
\XeTeXlinebreakskip = 0pt plus 1pt

%\setCJKfamilyfont{new}{方正苏新诗柳楷简体}
%\setCJKfamilyfont{note}{方正启体简体}
\setCJKfamilyfont{new}{Microsoft YaHei}
\setCJKfamilyfont{note}{Microsoft YaHei}
```

先到这里。
