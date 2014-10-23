#Fundamental Types

Demonstrating the size of fundamental types and it's use in `printf` function.

##	Recommended Reading Order

1.	[Hello World][hello]
2.	Fundamental Types

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

>	sizeof(char)	= 1, where it = A  
>	sizeof(int)	= 4, where it = 305419896  
>	sizeof(short)	= 2, where it = 0x1234 = 4660 = 011064  
>	sizeof(long)	= 8, where it = 0x1234567890123456  
>	sizeof(long long)	 = 8, where it = 1311768467284833366  
>	sizeof(float)	= 4, where it = 3.141593  
>	sizeof(double)	= 8, where it = 2.718285  
>	sizeof(a++)	= 4, where a = 1


[hello]: https://github.com/Rholais/LearnC/tree/master/hello "LearnC/hello at master"
[types]: https://github.com/Rholais/LearnC/tree/master/types "LearnC/types at master"

[deepin]: http://cdimage.linuxdeepin.com/releases/2014.1/deepin_2014.1_amd64.iso "deepin_2014.1_amd64.iso"