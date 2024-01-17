### Introduction

code for computing DE (differential entropy) and PSD (power spectral density) feature of signals in python.

```
input: 
    data-[n, m] n channels, m points of each time course,  
    window-integer, window lens of each segment in seconds, such as 1s
    fs-integer, frequency of singal sampling rate, such as 200Hz
    optional  f_bands, default delta, theta, aplha, beta, gamma

output:
	psd,de  [bands, channels, samples]
```

if you want to know more about the difference of methods in computing psd (shown in code), you can check [the following link](https://www.cnblogs.com/greystone/p/17971165).