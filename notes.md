# Learn Python the Hard Way

the book [Learn Python the Hard Way](https://learnpythonthehardway.org)

[typing.io](https://typing.io)

你在 GitHub 上看到过的最有意思的项目是什么？ [url](https://www.zhihu.com/question/23498424)

教你阅读Python开源项目代码 [url](https://zhuanlan.zhihu.com/p/22275595?refer=python-cn)

sign | name
---- | ---
+ |  plus
-  | minus
/  | slash
*  | asterisk
%  | percent
<  | less-than
>  | greater-than
<=  | less-than-equal
>= |  greater-than-equal
, | comma
. | period/full stop
? | question mark
! | exclamation mark
_ |  underscore
' ' |single-quotes
" " |double-quotes
\ | backslash



Escape	 | What it does.
---- | ---
\\ | 	Backslash (\)
\' | 	Single-quote (')
\" | 	Double-quote (")
\a | 	ASCII bell (BEL)
\b | 	ASCII backspace (BS)
\f | 	ASCII formfeed (FF)
\n | 	ASCII linefeed (LF)
\N{name} | 	Character named name in the Unicode database (Unicode only)
\r | 	Carriage Return (CR)
\t | 	Horizontal Tab (TAB)
\uxxxx | 	Character with 16-bit hex value xxxx (u'' string only)
\Uxxxxxxxx | 	Character with 32-bit hex value xxxxxxxx (u'' string only)
\v | 	ASCII vertical tab (VT)
\ooo | 	Character with octal value ooo
\xhh | 	Character with hex value hh


### 格式符
格式符为真实值预留位置，并控制显示的格式。格式符可以包含有一个类型码，用以控制显示的类型，如下:

格式符 | 意义
----|-----
%s |   字符串 (采用str()的显示)
%r |   字符串 (采用repr()的显示)
%c |   单个字符
%b |   二进制整数
%d |   十进制整数
%i |   十进制整数
%o |   八进制整数
%x |   十六进制整数
%e |   指数 (基底写为e)
%E |   指数 (基底写为E)
%f |   浮点数
%F |   浮点数，与上相同
%g |   指数(e)或浮点数 (根据显示长度)
%G |   指数(E)或浮点数 (根据显示长度)
%% |   字符"%"
