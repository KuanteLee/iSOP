# iSOP
http://cs224d.stanford.edu/syllabus.html <br>
https://readthispaper.com/tw/ <br>

logistic regression <br>
https://www.youtube.com/watch?v=xVHhlGOVN3Y <br>
https://www.yongxi-stat.com/logistic-regression/ <br>
https://reurl.cc/MXzQEW <br>

ＭＭoE <br>
https://www.twblogs.net/a/5efb8eead496dddbb541a3fc <br>
https://www.jianshu.com/p/2bfea809af3b <br>
https://reurl.cc/6Lqm6y <br>
<br>

# e
https://www.coursera.org/lecture/machine-learning-sas/split-search-6cm1g<br>
回歸樹用於分類<br>
https://scientistcafe.com/ids/splitting-criteria.html<br>
https://www.jmp.com/support/help/en/17.0/#page/jmp/statistical-details-for-the-splitting-criterion.shtml#<br>
https://www.cnblogs.com/chenyn68/p/3876835.html<br>
http://debussy.im.nuu.edu.tw/sjchen/MachineLearning/final/CLS_DT.pdf<br>
https://www.google.com/search?q=%E5%8D%A1%E6%96%B9%E6%B8%AC%E8%A9%A6+%E6%B1%BA%E7%AD%96%E6%A8%B9&rlz=1C5CHFA_enTW967TW967&ei=G461Y8mJH83z-QbE17iIDQ&ved=0ahUKEwiJg439kK78AhXNed4KHcQrDtEQ4dUDCA8&uact=5&oq=%E5%8D%A1%E6%96%B9%E6%B8%AC%E8%A9%A6+%E6%B1%BA%E7%AD%96%E6%A8%B9&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIFCCEQoAE6CggAEEcQ1gQQsAM6BQgAEKIESgQIQRgASgQIRhgAUMECWPwpYIMvaAVwAXgAgAGWAYgBlwiSAQQxNC4xmAEAoAEByAEKwAEB&sclient=gws-wiz-serp<br>
https://ithelp.ithome.com.tw/articles/10247440<br>
https://blog.csdn.net/on2way/article/details/88673075<br>



<br>
Transformer <br>
	• Sequence-to-sequence model (Seq2seq)
	• Input a sequence, output a sequence. The output length is determined by model


	• Simple network architecture based solely on attention mechanisms, dispensing with recurrence and convolutions entirely
	• more parallelizable and requiring significantly less time to train
	• 在 translation 任務取得很好的成果 （在明確列出來）

QK 計算兩個輸入的關聯性


# SQL

oracle data modeler <br>

## index 使用時機
在正常情況下, 資料表的欄位 index 可以增進擷取資料列的效率, 但是在一個資料表上多建立 index 並不一定可以得到好處. 原因是, 當確認一個具有 index 的 DML 操作時, 意含著 ORACLE 資料庫需去更新該 index 列, 所以當建立 index 的欄位越多, 資料庫的更新負荷也越大, 有時還會適得其反, 整體速度反而更慢. 因此建議使用 index 時間如下: <br>

* 當資料表某個欄位儲存的值範圍很大時 <br>
* 某個可能會出現大量空值的欄位 <br>
* 常用於 WHERE 子句或合併條件的欄位 <br>
* 預期 index 的資料量經常 <4% 的大資料量資料表 <br>

然而, 在下列情況下, 不建議使用 index: <br>

* 不經常用在條件式的欄位 <br>
* 需要經常更新的資料表 <br>
* 小資料量的資料表 <br>
* 預期 index 的資料量經常 >4% 的大資料量資料表 <br>

# 常用的 shell 命令
pwd: 獲取當前檔案的位置 <br>

ls: 顯示當前路徑下的文件. <br>
  -la: 同時顯示隱藏文件 <br>
  
cd ~: 回到默認路徑 <br>
cd /: 回到 root 路徑 <br>
  
mkdir: 創文件夾 <br>
 
touch: 創文件 <br>
 
rm: 刪除文件 <br>
  -rf: 強制刪除 <br>

clear: 清空 shell 命令 <br>

# Git 指命
git help <br>

git pull = git pull + git merge <br>
git fetch 把 repo 的更改內容拉到本地，但先不更改本地內容 <br>


// branch 太多不一定會用到，所以先 no checkout <br>
git clone --no-checkout url my_repo_name <br>
git status <br>

git remote url <br>

// 這邊在找到要的 branch 再 checkout <br>
git branch <br>
git checkout master <br>

git chechout -b new-branch <br>
git push -u origin new-branch <br>

git commit -am 'message' <br>
git push <br>

# 簡報技巧

恢復原狀型：
1. 掌握到底發生了什麼狀況（掌握現狀）
2. 視情況所需，將危害控制在最小限度（緊急處理）
3. 查明原因所在（分析原因）
4. 思考該如何修復（原因處理）
5. 研究對策，避免再度損壞（防止復發）

防杜潛在型：
1. 設定一個一旦發生會造成困擾的問題（設定問題）
2. 查明造成此為題的誘因（查明誘因）
3. 思考預防問題發生的對策（預防對策）
4. 思考問題發生時的對策（發生時的因應對策）

追求理想型：
1. 分析問題點的優缺點（資產盤點）
2. 選定追求的理想 ＝ 目標（選定理想）
3. 思考可達成理想的對策（行動計畫）

