![image](https://github.com/sarahxiaoqixu/Attention-gated-CNN/blob/master/1555641813(1).png)
基本结构：
卷积层（对输入的词向量进行卷积）==》attention-gated layer ==》max-over-time-pooling layer ==>fc ==> softmax  
示例图的参数设置：word vec维度`d`=4,句子长度`n`=7.基于输入的卷积核的size：`h`=2and 3;attention-gated  
层的卷积核的size：`K`=1and3。e<sub>i</sub>代表输入的 word vec， 输入的 sentence embedding 为  
    E<sub>1:n</sub>=[e<sub>1</sub>,e<sub>2</sub>...e<sub>n</sub>]<sup>T</sup>
