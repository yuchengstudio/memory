
1.什么是慢切斯特编码？
    在曼彻斯特编码中，每一位的中间有一跳变，位中间的跳变既作时钟信号，又作数据信号；从低到高跳变表示“1”，从高到低跳变表示“0”。还有一种是差分曼彻斯特编码，每位中间的跳变仅提供时钟定时，而用每位开始时有无跳变表示“0”或“1”，有跳变为“0”，无跳变为“1”。
    其中非常值得注意的是，在每一位的"中间"必有一跳变，根据此规则，可以得出曼彻斯特编码波形图的画法。例如：传输二进制信息0，若将0看作一位，我们以0为中心，在两边用虚线界定这一位的范围，然后在这一位的中间画出一个电平由高到低的跳变。后面的每一位以此类推即可画出整个波形图。 [1]  
    
    
2.非常有用的参考：
https://github.com/yuchengstudio/memory/blob/master/UNIO%20EEPROM%20-%20-EEPROM/01185b_cn.pdf

3.c语言参考代码：
https://github.com/yuchengstudio/memory/blob/master/UNIO%20EEPROM%20-%20-EEPROM/AN1185.zip
