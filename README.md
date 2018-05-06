- [信号包络](#)
- [信号的相关性](#)

# 信号包络
&emsp;&emsp;将一段时间长度的高频信号的峰值点连线,就可以得到两条曲线,上方(正的)一条线和下方(负的)一条线,这两条线就叫包络线.包络线(低频)反映了高频信号幅度变化的曲线.对于等幅高频信号,其中的两条包络线就是平行线.如下图:

![信号包络](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems001.png?raw=true?raw=true) 

&emsp;&emsp;当用一个低频信号对一个高频信号进行幅度调制(即调幅),低频信号就成了高频信号的包络线.这样的信号称为调幅信号.

# 信号的相关性
&emsp;&emsp;在信号处理中,经常要研究两个信号的相似性,或者一个信号经过一段时间延迟后自身的相似性,以便实现信号检测,识别与提取等.互相关描述两个信号之间(不同时刻)的相关性,自相关描述信号自身间(不同时刻)的相关性.信号的相关性记为`r`.
&emsp;&emsp;对于两个函数(或信号)![](http://latex.codecogs.com/gif.latex?f(t))和![](http://latex.codecogs.com/gif.latex?g(t))的`r`计算如下:

![r计算](https://github.com/gaosiyan/Signals-and-Systems/blob/master/image/Signals-and-Systems002.png?raw=true?raw=true) 

&emsp;&emsp;其中![](http://latex.codecogs.com/gif.latex?\left\langle f(t),g(t)\right\rangle)是两个函数的内积,![](http://latex.codecogs.com/gif.latex?||f(t)||∣∣f(t)∣∣)

其中`$$`是两个函数的内积,`$||f(t)||$`是函数`$f(t)$`的模,按照内积和模的计算公式展开后:

![](http://latex.codecogs.com/gif.latex?f(t)),g(t)\right\rangle⟨f(t),g(t)⟩是两个函数的内积,||f(t)||∣∣f(t)∣∣是函数f(t)f(t)的模,按照内积和模的计算公式展开后:
