# 雙碼注音

  給**注音**使用者的雙拼輸入法。學習高效率的雙拼輸入法之前不再需要額外學習漢語拼音。
  按鍵定位類似漢語拼音、通用拼音，但是拼音規則為注音的拼音規則。

## 鍵位圖
  ![KB layout](https://i.imgur.com/OutagKQ.jpg)

## 說明
  這是一個 cin 碼表的輸入方案，需要安裝任何一款可讀 cin 碼表的輸入法，方可使用：

  > <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="創用 CC 授權條款" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />本著作【雙碼注音輸入法】係採用<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">創用 CC 姓名標示-相同方式分享 4.0 國際 授權條款</a>授權。
  
  > - 雙碼注音歡迎各種不同的輸入法實作。
  > - 本 CIN 實作為 **MIT** 授權。
  > - 雙碼注音的第一目標是【**普及率**】
  
  > - 雙碼注音是一種輸入法，不是檢字法。
  > - 不適合大量輸入人名這種需要*精確*定位到某個字的情況。

### 輸入規則   
  1. 兩碼一字：第一碼聲母，第二碼韻母。（第三碼可用數字１～５輸入聲調，第三碼非必要，可省略。）
  2. 虛韻母：ㄓㄔㄕㄖ　ㄗㄘ厶  這些可以獨存的聲母（其實是韻母省略）要多打一個虛韻母「ㄭ」在後。  「ㄭ」放在 `I 鍵`上，用 emoji: 😬 表示，因爲發音時嘴形類似。
  3. 0️⃣聲母：介音與所有的韻母（ㄧㄨㄩ、ㄚㄛㄜㄝ、ㄞㄟㄠㄡ、ㄢㄣㄤㄥ及兒化韻母ㄦ）獨存時，先按零聲母，再按對應的按鍵。  零聲母放在 `E 鍵`上，用 emoji: 🈳/0️⃣ 表示，因爲`Empty`。
  
  如此，所有的注音符號音節（但不包括尖團音），全部編碼成兩碼了。
  另外，目前是12345輸入聲調，但聲調不是必要的；67890選字。
  此外，ㄗ放 `W 鍵`的設計，參考了法語鍵盤（azerty keyboard）`Z 鍵` `W 鍵` 交換的設計。

#### 輸入範例與比較
  ||我|用|雙|碼|注|音|輸|入|中|文|漢|字|
  |--|--|--|--|--|--|--|--|--|--|--|--|--|
  |雙碼注音|uo|yf|oc|ma|au|id|ou|ru|al|ud|hk|wi|
  |微軟注音|ji3|m/4|gj;␣|a83|5j4|up␣|gj␣|bj4|5j/␣|jp6|c04|y4|
  |微軟拼音|wo|yong|shuang|ma|zhu|yin|shu|ru|zhong|wen|han|zi|
  |漢語拼音|wǒ|yòng|shuāng|mǎ|zhù|yīn|shū|rù|zhōng|wén|hàn|zì|
  |注音符號|ㄨㄛˇ|ㄩㄥˋ|ㄕㄨㄤ|ㄇㄚˇ|ㄓㄨˋ|ㄧㄣ|ㄕㄨ|ㄖㄨˋ|ㄓㄨㄥ|ㄨㄣˊ|ㄏㄢˋ|ㄗˋ|

#### 其他應用
  - 點字
  - 旗語
  - 手語
	
### 其他規則（不知道也不影響正常使用）
  預設使用聲調當**輔助碼**  
     `雙拼 + 【;a】 = 一聲；1 向下移動2排`  
     `雙拼 + 【;s】 = 二聲；2 向下移動2排`  
     `雙拼 + 【;d】 = 三聲；3 向下移動2排`  
     `雙拼 + 【;f】 = 四聲；4 向下移動2排`  
     `雙拼 + 【;】  = 輕聲；`	 
  手機上的輸入法可能無法直接輸入聲調，這是設計給這種情況用的。
  
### 檔名解釋
  - `double_bopomo_keyboard_layout.jpg`：雙碼注音的基本鍵盤佈局圖。
  - `BIG5_double_bopomo.cin`：大五碼雙碼注音 + 大五碼「三碼」注音 CIN 檔（雙碼注音 + 一碼聲調（數字））。
  - `CNS_double_bopomo.cin`：全字庫雙碼注音 + 全字庫「三碼」注音 CIN 檔（雙碼注音 + 一碼聲調（數字））。 
  - `README.md`：本檔案。

## 相關連結
  - [Youtube影片](https://youtu.be/SD2iaUONg7A)
  - [PTT發佈頁、討論頁](https://www.ptt.cc/bbs/IME/M.1572622340.A.FEA.html)

## 截圖
  > ![Heatmap](https://imgur.com/UUiUJxB.jpg)  
  鍵盤熱力圖
  
## 網友提供的相關圖片
  > ![Layout by xcv123321](https://i.imgur.com/xq0NrR6.png)  
  由[xcv123321](https://github.com/xcv123321)提供的雙碼注音按鍵佈局圖
  
  > ![Heatmap by jamessa](https://i.imgur.com/N1o1J4K.jpg)  
  由[jamessa](https://github.com/jamessa)提供的雙碼注音按鍵熱力圖，這是詳細的[分析結果](http://patorjk.com/keyboard-layout-analyzer/#/load/p6bsg5Fx)
  
## 銘謝
  1. [gugod](https://github.com/gugod) 協助刪除CIN檔重複的字詞。