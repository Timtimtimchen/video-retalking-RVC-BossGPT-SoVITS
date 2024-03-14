# RVC-Boss/GPT-SoVITS 語音合成模型

## 1.初始執行畫面
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/A.png)

## 2.把音檔放進檔案根目錄
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/b.png)

## 3.設定變數
#### 1.過濾人聲音
#### 2.分割音檔
#### 3.音檔位置
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/C.png)


## 4.分割音檔合成list
list位置在框內位置 可自訂
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/D.png)

## 5.Speech to text proofreading tool
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/e.png)

## 6.終端給WebUI網址
確認沒問題就可關閉網頁

## 7.第二個頁面(1-gtp-sovits-TTS)
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/F.png)
設置實驗名也就是模型名，不要有中文！然後第一個輸入的是標註文件路徑，注意是文件路徑！示例：/content/GPT-SoVITS/output/asr_opt/slicer_opt.list 注意後面的文件名必須要輸進去！打不開就再三檢查路徑是否正確！必須要有.list的後綴！！！第二個輸入的是切分音頻文件夾路徑 示例：/content/GPT-SoVITS/output/slicer_opt。注意複製的路徑都不能有引號！！！千萬不能有引號！然後點一鍵三連。結束 /content/GPT-SoVITS/logs 裡會有檔案 沒有就是錯

## 訓練(1B-Fine-tuned training)
點進 1B-Fine-tuned training 兩個按鈕都按 
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/g.png)
如報錯就是gpu size要改


## 1c-inference
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/h.png)
GPT models list 跟 SoVITS models list 都要選數字大的 如果沒選項點refresh 再來 Open TTS inference WEBUI打勾

## 終端給新網頁 雙擊
![image](https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/i.png)
給十秒內的影片並給影片中文內容
 再來給他你想讓他講的句子 按start
 音檔生成在右手邊

## 加video-retalking使影片更生動然


<video controls  title="Title">
<source id="mp4" src="https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/蔡英魂找中國單挑.mp4" type="video/mp4"></video>

<video controls src="https://github.com/Timtimtimchen/video-retalking-RVC-BossGPT-SoVITS/blob/master/PHOTO/蔡英魂推薦我讀研究所.mp4" title="Title"></video>
</videos>
