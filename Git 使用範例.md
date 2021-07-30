# Git 使用範例

### 1.下載Git

Git官方網站 <https://gitforwindows.org/>

TortoiseGit官方網站 <https://tortoisegit.org/>

Git 使用手冊 <https://git-scm.com/book/en/v2>

### 2.終端機查詢是否有安裝成功

* 在終端機裡面輸入 : `git --version`，如果有則會看到下面畫面

  <img src="C:\work\Git\Git-learner\picture\002version_check.PNG" alt="002version_check"  />

* 如果沒有看到則要重新安裝

### 3.設定個人資料

* 輸入使用者姓名 : ` git config --global user.name "shino8188`

* 可以用`git config --global user.name`來查是否輸入成功。

  ![003_check_user_name](C:\work\Git\Git-learner\picture\003_check_user_name.PNG)

* 輸入使用者的mail : `git config --global user.email "shino8188@gmail.com"`

* 可以用`git config --global user.email`來查詢是否輸入成功。

![003_check_user_email](C:\work\Git\Git-learner\picture\003_check_user_email.PNG)

### 4.建立Github帳號





* 查詢git設定內容 : `git config --list`

![72316309_2739111376108490_535994150261096448_n](C:\Users\shino\Downloads\72316309_2739111376108490_535994150261096448_n.jpg)





# 教學

1. 為什麼要學GIT<https://www.youtube.com/watch?v=PNEM7CH3ZAg&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=8>
2.  Git 安裝流程<https://www.youtube.com/watch?v=VufCg58gysE&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=28>
3.  終端機指令 cd 前往<https://www.youtube.com/watch?v=95IibQuSKDA&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=28>
4.  環境與設定<https://www.youtube.com/watch?v=o1vHhRjQv0A&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=2>
5. 常用終端指令分享<https://www.youtube.com/watch?v=4dLiAVbfS5Q>
6. Git基本教學<https://www.youtube.com/watch?v=mCzptNYsE30&t=243s>
7.  Sourcetree軟體教學<https://www.youtube.com/watch?v=qAowFThM50c&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=5>
8.  新增遠端數據庫 repo<https://www.youtube.com/watch?v=QF00ThvS688&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=14>
9. 回顧練習 <https://www.youtube.com/watch?v=stD3_Ke6blw&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=3> 
10.  Git 指令縮寫<https://www.youtube.com/watch?v=o0ngrUEh3hU&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=16>
11.  Git、GitHub 差異<https://www.youtube.com/watch?v=kajih2OHig0&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=27>
12.  Git Repository 中文翻譯<https://www.youtube.com/watch?v=WE189kyuVgs&list=PLYrA-SsMvTPOZeB6DHvB0ewl3miMf-2tj&index=12>
13.  遠端數據庫詳解<https://www.youtube.com/watch?v=50UgfhiXcZI&list=PLYrA-SsMvTPOZeB6DHvB0ewl3miMf-2tj&index=13>
14.  Bitbucket 服務介紹<https://www.youtube.com/watch?v=cEl51LHp-40&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=7>
15.  HEAD 指標、checkout 前往<https://www.youtube.com/watch?v=g2HhCe_tmuY&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=15>
16.  遠端數據庫線圖介紹<https://www.youtube.com/watch?v=zwqp2tnU-eA&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=24>
17.  檔案還原技巧<https://www.youtube.com/watch?v=sM2_e8ysjyg&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=19>
18.  練習回顧<https://www.youtube.com/watch?v=uHA0Xpcgip0&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=28>
19.  分支介紹<https://www.youtube.com/watch?v=ESpqx1GK-q0&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=9>
20.  開設、合併分支<https://www.youtube.com/watch?v=8Tzy2xyjF_U&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=27>
21.  快轉與取消快轉機制<https://www.youtube.com/watch?v=Rt4HGw5U2_Y&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=18>
22.  分支情境演練<https://www.youtube.com/watch?v=SRtGbeDNsH8&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=39>
23.  分支練習一<https://www.youtube.com/watch?v=M_ioHIuY2jg&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=41>
24.  分支練習二<https://www.youtube.com/watch?v=lE64TfJTSaY&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=29>
25.  分支練習三<https://www.youtube.com/watch?v=oYQDkUQYE5U&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=36>
26.  Git Reset 版本還原<https://www.youtube.com/watch?v=Us2GDj_DqMs&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=6>
27.  Git Reset 實際演練<https://www.youtube.com/watch?v=TPCmsdPzq-w&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=23>
28.  Git Reset 參數介紹<https://www.youtube.com/watch?v=FNOGNHz1PiI&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=11>
29.  Git Reflog 還原大招<https://www.youtube.com/watch?v=4--hBTkhbuI&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=39>
30.  Git 發 GitHub PR 請求流程 pull request<https://www.youtube.com/watch?v=y5rb1ggm6OU&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=4>
31.  Git Merge 衝突解決<https://www.youtube.com/watch?v=-6xhsLQQJBc&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=12>
32.  遠端衝突解決<https://www.youtube.com/watch?v=ewSWSGIe0CM&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=10>
33.  Git flow 簡介<https://www.youtube.com/watch?v=L4iAIT03Wb0&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=25>
34. GitHub flow 講解<https://www.youtube.com/watch?v=ELkHzzpT17c&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=27>
35.  GitHub flow 線上三人實際演練<https://www.youtube.com/watch?v=C_u6RLXixLY&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=2>
36. GitHub 保護分支機制<https://www.youtube.com/watch?v=hQxUoGU1vGw&list=RDCMUC-b2nGm0xLzic38Byti0VjA&index=20>
37. Git 分支教學上集<https://www.youtube.com/watch?v=K6NhMxjB1zQ&list=PLYrA-SsMvTPOZeB6DHvB0ewl3miMf-2tj&index=37>
38. Git 分支教學下集<https://www.youtube.com/watch?v=EswB-4KGGjk&list=PLYrA-SsMvTPOZeB6DHvB0ewl3miMf-2tj&index=38>

