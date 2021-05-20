# CVE-2020-0787-EXP-ALL-WINDOWS-VERSION

#### 增加回显到文件

- 输入同目录下input.bat
- 输出同目录下output.txt

![Snipaste_2021-05-20_16-05-08](C:\_code\weapons\ccdragon\CVE-2020-0787-EXP-ALL-WINDOWS-VERSION\Snipaste_2021-05-20_16-05-08.png)

顺便也把CreateProcessAsUser的flag位改成了CREATE_NO_WINDOW

似乎是任意移动恶意的dll到system32目录然后加载dll(不太懂),感觉挺难用管道回显的,感觉文件回显也还行8

#### 申明 ####

作者poc仅供研究目的,如果读者利用本poc从事其他行为,与本人无关

#### 介绍
CVE-2020-0787-EXP Support ALL Windows Version

![pic](https://ftp.bmp.ovh/imgs/2020/06/bcf797d23480bb10.png)