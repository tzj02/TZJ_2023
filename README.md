# TZJ_2023
这是在完成大创期间的部分工作：
1.利用verilog语言实现RO震荡期的模拟
2.利用所设计的14阶LFSR的随机输出实现了对不同频率RO震荡期的模拟
3.随机码流通过哈密顿回路，在哈密顿回路末端输出，与原本的输入码流通过对比电路检测
4.对比电路的阈值设定为：若一个字节内有三个及以上比特不同，且连续三个字节均有此情况，则不通过比对，发出警报；反之，通过比对
