Linux CTF1
step1: ssh -p2200 lab@120.114.62.89

step2: yes

step3: password: lab

step4: ls 找到flag(文件檔)

step5: cat flag
![](https://github.com/ase78920019/assignment/blob/master/picture/Linux1.PNG)

Linux CTF2
step1: pwd (找到自己的絕對路徑)

step2: 已在 home/lab

step3: ls -al  找隱藏檔案

step4: file .hiidden(發現是文件檔)

step5: cat .hidden

![](https://github.com/ase78920019/assignment/blob/master/picture/Linux2.PNG)


Linux CTF3
step1: cat hex.txt

step2: 發現是16進位

step3: xxd -r -p hex.txt (16進位轉字串)
![](https://github.com/ase78920019/assignment/blob/master/picture/Linux3.PNG)


Linux CTF4
step1: cat base64.txt

step2: 發現是base64編碼

step3: base61 -d base64.txt (base64解碼)
![](https://github.com/ase78920019/assignment/blob/master/picture/Linux4.PNG)

Linux CTF5
Linux CTF6
step1: ps -aux (列出服務)

step2: /bin/flag (執行他)

![](https://github.com/ase78920019/assignment/blob/master/picture/Linux6.PNG)


Linux CTF7
step1: netstat -ano (列出網路服務)

step2: curl http://127.0.0.1/ (80 Port有你要的答案 -> 取得http://127.0.0.1/的網頁內容)

![](https://github.com/ase78920019/assignment/blob/master/picture/Linux7.PNG)


Linux CTF8
step1: cd tmp/

step2: mkdir 610145

step3: cd 610145/

step4: wget http://120.114.62.39/ForYou.tar.gz (下載)

step5: tar zxvf ForYou.tar.gz  (解壓縮)

step6: file ForYou (文件檔)

step7: cat ForYou

![](https://github.com/ase78920019/assignment/blob/master/picture/Linux8.PNG)


Linux CTF9
step1: wget http://120.114.62.39/TobeExe

step2: ls

step3: file TobeExe

step4: strings TobeExe (找到BreakAll開頭)

![](https://github.com/ase78920019/assignment/blob/master/picture/Linux9.PNG)


Linux CTF10
step1: wget http://120.114.62.39/reverse

step2: ls

step3: file reverse

step4: strings reverse (找到BreakAll開頭)
![](https://github.com/ase78920019/assignment/blob/master/picture/Linux10.PNG)


