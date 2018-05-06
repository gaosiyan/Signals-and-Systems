- [信号包络](#)
- [信号的相关性](#)
- [ZC序列](#zc)

# 信号包络
&emsp;&emsp;将一段时间长度的高频信号的峰值点连线,就可以得到两条曲线,上方(正的)一条线和下方(负的)一条线,这两条线就叫包络线.包络线(低频)反映了高频信号幅度变化的曲线.对于等幅高频信号,其中的两条包络线就是平行线.如下图:

![信号包络](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems001.png?raw=true?raw=true) 

&emsp;&emsp;当用一个低频信号对一个高频信号进行幅度调制(即调幅),低频信号就成了高频信号的包络线.这样的信号称为调幅信号.

# 信号的相关性
&emsp;&emsp;在信号处理中,经常要研究两个信号的相似性,或者一个信号经过一段时间延迟后自身的相似性,以便实现信号检测,识别与提取等.互相关描述两个信号之间(不同时刻)的相关性,自相关描述信号自身间(不同时刻)的相关性.信号的相关性记为`r`.
&emsp;&emsp;对于两个函数(或信号)`f(t)`和`g(t)`的`r`计算如下:

![r计算](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems002.png?raw=true?raw=true) 

&emsp;&emsp;其中`<f(t),g(t)>`是两个函数的内积,`||f(t)||`是`f(t))`的模,按照内积和模的计算公式展开后:

![r计算](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems003.png?raw=true?raw=true) 

&emsp;&emsp;`r>0`正相关,`r=0`不相关,`r<0`负相关(方向不同),`r`越大相关性越强.

&emsp;&emsp;对于序列`f`和`g`的相关性可以表示如下:

![r计算](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems004.png?raw=true?raw=true) 


&emsp;&emsp;注意点:
* 函数的模平方等于自身的内积;
* 函数的模和内积要除以区间长度,而序列的不用.

# ZC序列

&emsp;&emsp;`ZC`序列是`CAZAC`序列的一种:
* 恒包络特性;任意长度的`CAZAC`序列幅值恒定;
* 理想的周期自相关特性;任意`CAZAC`序列移位`n`位后,n不是CAZAC序列的周期的整倍数时,移位后的序列与原序列不相关,而且两个互质的`ZC`序列的互相关也接近于0;
* 傅里叶变换后仍然是`CAZAC`序列;
* 
&emsp;&emsp;`ZC`序列的生成公式:

![ZC计算公式](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems005.png?raw=true?raw=true) 









