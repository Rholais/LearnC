#Hello World

Introducing the use of `\` in a string.

##	Recommended Reading Order

1.	Hello World

##	Platform Infomation

All these codes have been tested by my [Deepin 2014.1 amd64][deepin].

>	$ uname -r  
>	3.13.0-37-generic

>	$ uname -m  
>	x86_64

>	$ make -v  
>	GNU Make 3.81

>	$ gcc -v  
>	gcc version 4.8.2 (Ubuntu 4.8.2-19ubuntu1) 

##	Running Result

>	Hello World!  
>	C语言的字符串两边用双引号"..."  
>	如果需要输出双引号"，需要在"前面加\  
>	其中反斜杠\为转意符，其后配合字母、符号可以输出特殊字符。  
>	如果需要输出反斜杠\，在字符串内要写作\\  
>	\n为换行符。  
>	这里另起一行了  
>	另一个	重要	symbol	是	制表符\t  
>	它	可以	使	输出	变得	整齐  
>	其他常用特殊字符：  
>	\'	单引号'  
>	\0	(null)，字符串结尾标示符  
>	\?	问号?  
>	\b	退格符(backspace)  
>	\r	回车符(return)


[hello]: https://github.com/Rholais/LearnC/tree/master/hello "LearnC/hello at master"
[deepin]: http://cdimage.linuxdeepin.com/releases/2014.1/deepin_2014.1_amd64.iso "deepin_2014.1_amd64.iso"