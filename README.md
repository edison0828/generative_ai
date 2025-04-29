# generative_ai

- 姓名：林冠宇
- 系級：資工 115
- 課程名稱：生成式 AI：文字與圖像生成的原理與實務\_國立臺灣師範大學衛星課程
- 修課學期：113-2
- 檔案命名格式(HW #week)：HW2表示第二周作業，如果有跳過表示當周無作業

## 檔案說明

- `HW1.ipynb`: 畫一個函數圖形 (leaky relu) 並說明

  ### 圖形展示

  ![圖片](screenshots/hw1.png)

- `HW2.ipynb`: 設計並訓練一個全連接 (Fully-Connected) 的深度神經網路 (DNN)，用以進行 MNIST 手寫數字辨識。

  ### 測試效果展示

  實際在測試集上預測效果圖：  
  <img src="screenshots/hw2.1.png" alt="圖片1" width="49%" height="400px"> <img src="screenshots/hw2.2.png" alt="圖片2" width="49%" height="400px">

  在 gradio 上手繪數字進行測試：  
  ![圖片三](screenshots/hw2.3.png)

- `HW3.ipynb`: 主題二、研究GAN背後原理，試著用自己的方式解釋Cross Entropy、KL divergence。

- `HW4.ipynb`: 建立自己的 benchmarks 測試不同的 LLM，這邊提出了兩個問題，分別是算字數問題以及經典的電車難題，主要想測試 LLM 的邏輯推理能力。

- `HW6.ipynb`: 用OpenAI API打造自己的對話機器人，實作了一個選股策略建議系統，使用者只需輸入簡單的投資需求，AI 助手就會自動產生一份適合的交易策略。

- `HW7.ipynb`: 延續HW6，改成可持續對話的ai聊天機器人。

- `HW8.ipynb`: 台灣民法 RAG 問答助理: 建立一個使用 檢索增強生成 (RAG) 技術的智慧問答助理，專門回答與台灣民法相關的問題。

- `HW9.ipynb`: 使用者輸入一份pdf格式的論文，利用大型語言模型 (LLM) 和鏈式思考 (Chain-of-Thought, CoT) 的能力，幫助使用者快速整理並了解研究論文的核心內容和論證邏輯。

