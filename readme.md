
 Copyright 2016, Sayem Mohammad Siam
 siam@ualberta.ca
 This is an implementation of an algorithm described in http://ieeexplore.ieee.org/abstract/document/7989671/. 
 Modified the original code of  Niko Sünderhauf which can be found https://openslam.org/openseqslam.html
 The functions doProcessing, doFindMatches (doFindMatchesModified), doDifferenceMatrix, DefaultParameters are mainly modified.
 Other than this files, some parameters of the other files are modified.
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
