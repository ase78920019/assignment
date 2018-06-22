Web-1
step1: Ctrl+U (檢視網頁原始碼)
step2: Ctrl+F (找BreakALL)
Web-2

![](https://github.com/ase78920019/assignment/blob/master/picture/web5.PNG)

step1: 在網址後方加上 : /robots.txt ==> 出現Disallow: /secret 

step2: 把/robots.txt 改成 /secret

step3: 把flag.txt的編碼解開 (先用hex to string 再用base64)

Web-3

step1: curl -v http://120.114.62.89:2014/no_flag_is_here.php

step2: curl -v http://120.114.62.89:2014/index.php
step3: 找到breakall




![](https://github.com/ase78920019/assignment/blob/master/picture/curl%20(1).PNG)
![](https://github.com/ase78920019/assignment/blob/master/picture/curl%20.PNG)
Web-4
Web-5
在網址處將 index.php 改成/flag

沒東西 -> 回到上層(../) -> 直到出現flag

yourdearstudenthomework

Web-6
