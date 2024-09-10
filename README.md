<p align="center">
  <h2 align="center">NOVA CHAT</h2>
  <p align="center">
    一款能讓虛擬主播開口說話、即時互動的App，NOVA Chat 讓直播不再只有文字！<br>
  </p>
  <p align="center">
    <a href="https://discord.gg/GvX9sM3Z">
        <img src = "https://dcbadge.limes.pink/api/server/GvX9sM3Z?style=flat">
    </a>
    &ensp;
    <a href="https://twitter.com/nova_assistant/">
        <img src = "https://img.shields.io/twitter/follow/nova_assistant">
    </a>
    &ensp;
    <a href="https://novahelper.ai/">
        <img src = "nova-ai.svg">
    </a>
  </p>
</p>

## 基礎功能

### 文字轉語音
NOVA Chat 可以將觀眾的留言或文字輸入即時轉換為 AI 聲音，模擬虛擬主播的語調和個性。

### Live2D 模型動作觸發
當觀眾的留言被轉換成語音時，NOVA Chat 能根據不同的留言內容，觸發 Live2D 模型的對應動作或表情，增強虛擬主播的互動性和表現力。

## 用途

### VTuber 影片製作
自媒體創作者可以利用 NOVA Chat 將觀眾留言融入影片製作過程，增強互動性和真實感，使影片更具吸引力。

### 即時直播互動
在直播中使用 NOVA Chat，可以即時將觀眾的留言轉換為語音，並同步觸發虛擬主播的動作，讓直播更加生動有趣，拉近實況主與觀眾的距離。

### 聲音輔助
對於不擅長語言表達的創作者，NOVA Chat 可以幫助他們自信地表達觀點，保持內容個性化。同時也可以作為直播主聲音沙啞時的替代方案。

## 特點

### 提升互動體驗
讓觀眾的留言不僅僅停留在文字層面，通過 AI 聲音和 Live2D 動作的同步展示，提升觀眾與實況主之間的互動感，讓觀眾感覺到自己是節目的一部分。

### 降低創作門檻
對於不擅長語言表達或無法進行複雜直播設定的創作者，NOVA Chat 是一個簡單易用的工具，讓他們能輕鬆創作內容。

### 個性化體驗
NOVA Chat 可以根據觀眾的不同反應和留言內容，自動調整 AI 聲音和 Live2D 模型的表現，提供每次獨特的互動體驗，增加內容的多樣性。

# NOVA CHAT 設置教學

### 1. 設置 VTube Studio
+ 打開並啟動 VTube Studio 應用程式。

  ![vTube icon](vTube.png)
+ 進入 VTube Studio 的 API 設置欄，輸入 API 密鑰 8051，並點擊 “確認 API 調用” 按鈕。

  ![vTube Setting](vTube-setting.png)
### 2. 配置 NOVA CHAT 應用程式
+ 打開 NOVA CHAT 應用程式。
+ 點擊 "設定" 按鈕，Vtube Studio 會提示是否同意掛載第三方應用程式，確認即可。
  
  ![Nova Setting](Nova-setting.png)
### 3. 使用 NOVA CHAT 功能
+ 您可以通過鍵盤輸入，按下 Enter 或點擊 “送出” 按鈕來發送訊息。

  ![Text Input](text-input.png)
+ 連接 YouTube 直播間: 輸入 YouTube 直播間的連結，NOVA CHAT 會自動抓取聊天室內容。

  ![YT Setting](yt-setting.png)
## Q&A
  1. 甚麼是設置按鈕？
      + 設置按鈕用於確保 NOVA CHAT 與 VTube Studio 是否正常串接。
  2. 甚麼是 YouTube 串接？
      + YouTube 串接只能抓取直播聊天室的內容。
  3. 如何將語音輸入至 OBS？
      + 打開 OBS 並使用應用程式擷取功能來捕捉語音輸入。
  4. 留言朗讀設定？
      + 您可以調整留言朗讀的時間間隔。
  5. 聲音類型選擇？
      + 您可以選擇喜歡的語音包，個性化您的體驗。
## Road Map - 未來預計追加功能
  1. 支援多平台直播間。 Ex twitch ...
  2. 支援其他語言介面 (英文 日文) 
  3. 使用者可以克隆(clone)自己的聲音。
  4. Superchat 贈送訂閱 優先朗讀功能。
  5. Superchat 贈送訂閱 訂製特效
  6. 常用設定檔儲存 調整聲音音量、語速、音準高低的部分可以儲存設定
  7. 進階朗讀設定
      + 可朗讀emoji
      + Ban word 禁詞功能，聊天室如果打太over的詞彙可以跳過或消音
  8. 新增 Vtuber 動畫後台控制 動畫表情包自訂功能。
  9. 優化 OBS 直播室適配性。
  10. 串接 AI LLM 聊天機器人，支援自訂義 AI 聊天機器人。
  11. 導入 捏臉v皮選擇
