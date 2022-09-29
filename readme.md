I used Flann libray for the Approximate nearest neighbour calculation.
 didn't implement the matching computation in the doFindMatchesModifed parallely so it may take longer time than the original
 seqSlam implementation which has implemented matching computation parallely

## Tests
* Matlab 8.5.0.197613 (R2015a)
* 64-bit
* Ubuntu 14.04.5

```
>> cd demo
>> demo
```
<img src="https://raw.githubusercontent.com/ICRA2017/Fast-SeqSLAM/reproducible/demo/figure_1.png">
<img src="https://raw.githubusercontent.com/ICRA2017/Fast-SeqSLAM/reproducible/demo/figure_2.png">
<img src="https://raw.githubusercontent.com/ICRA2017/Fast-SeqSLAM/reproducible/demo/figure_3.png">
