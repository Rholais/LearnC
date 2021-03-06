#Formatted Output

Demonstrating the usage of `wprintf`.

##	Recommended Reading Order

1.	[Hello World][hello]
2.	[Fundamental Types][types]
3.	Formatted Output
4.	[Operators][operators]
5.	[Contorl Structures][ctrl]
6.	[Formatted Input][wscanf]
7.	[Array][array]
8.	[Type Casting][cast]
9.	[Pointers][ptr]
10.	[Functions][func]
11.	[User Defined Types and Structs][struct]
12.	[Function Pointer][fp]
13.	[Random-Number Generator][rand]

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

>	Integer formats:  
>	   Decimal: -9234  Justified: -009234  Unsigned: 4294958062  
>	Decimal -9234 as:  
>	   Hex: FFFFDBEEh  C hex: 0xffffdbee  Octal: 37777755756  
>	Digits 10 equal: 
>	   Hex: 16  Octal: 8  Decimal: 10  
>	Characters:  
>	         h    h    位    位  
>	Strings:  
>	                 computer  
>	                     comp  
>	   8位变长万国码格式                      8位变  
>	Real numbers:  
>	   251.736600 251.74 2.517366e+02 2.517366E+02  
>	
>	Address as:   0x7fffe6f277a0  



[hello]: https://github.com/Rholais/learn-c/tree/master/hello "learn-c/hello at master"
[types]: https://github.com/Rholais/learn-c/tree/master/types "learn-c/types at master"
[wprintf]: https://github.com/Rholais/learn-c/tree/master/wprintf "learn-c/wprintf at master"
[operators]: https://github.com/Rholais/learn-c/tree/master/operators "learn-c/operators at master"
[ctrl]: https://github.com/Rholais/learn-c/tree/master/ctrl-structures "learn-c/ctrl-structures at master"
[wscanf]: https://github.com/Rholais/learn-c/tree/master/wscanf "learn-c/wscanf at master"
[array]:  https://github.com/Rholais/learn-c/tree/master/array "learn-c/array at master"
[cast]: https://github.com/Rholais/learn-c/tree/master/cast "learn-c/cast at master"
[ptr]: https://github.com/Rholais/learn-c/tree/master/ptr "learn-c/ptr at master"
[func]: https://github.com/Rholais/learn-c/tree/master/func "learn-c/func at master"
[struct]: https://github.com/Rholais/learn-c/tree/master/struct "learn-c/struct at master"
[fp]: https://github.com/Rholais/learn-c/tree/master/fp "learn-c/fp at master"
[rand]: https://github.com/Rholais/learn-c/tree/master/rand "learn-c/fp at rand"

[deepin]: http://cdimage.linuxdeepin.com/releases/2014.1/deepin_2014.1_amd64.iso "deepin_2014.1_amd64.iso"
