# kaldi-gop
Compute Goodness of Pronunciation (GOP) bases on Kaldi.

根据 junbo zhang  github  GOP 代码，添加新的Makefile
```
编译步骤
1, 先根据kaldi自身代码编译
2, 把gop gopbin 拷贝kaldi的src下
3, 在gop gopbin 下分别make
4, 在egs/gop-compute/，sh run.sh
```
