# 主題：AI新浪潮 — 生成式AI如何重塑我們的日常

```
講者：林俊良教授（國立中興大學電機系）  
日期：114年6月10日
```

---

## 一、前言

本次演講由中興大學電機系林俊良教授主講，深入介紹了生成式AI（Generative AI）在圖像、語言、音樂等多個領域的發展與應用。講者以實際例子帶出AI如何逐漸融入日常生活，並從技術面探討了神經網路的發展歷史與現代生成模型的進展。整場內容從圖靈測試談起，涵蓋ChatGPT等代表性模型，進而探討Transformer架構對AI進步的關鍵貢獻。

---

## 二、關鍵技術與研究成果

### 1. 類神經網路與深度學習的基礎

人工神經網路（ANN）模仿生物神經系統，利用權重與激勵函數構成多層架構以進行分類與預測。早期的RNN（Recurrent Neural Network）雖然能處理序列資料，但易受梯度消失問題影響。Hochreiter與Schmidhuber於1997年提出的LSTM（Long Short-Term Memory）成功克服此限制，在語音辨識、語言模型與時間序列預測中廣泛應用，成為許多後續生成式模型的基礎之一【3】。

### 2. Transformer架構與語言生成模型

Vaswani等人在2017年提出Transformer架構【1】，透過Self-Attention機制可同時處理整個輸入序列的語意關係，大幅提升語言理解與生成能力。該架構已成為當代語言模型的核心基礎，如OpenAI推出的GPT系列便是以此為基礎建構。其中Radford等人在2020年發表的GPT-3論文【4】，展示了少量示例學習（few-shot learning）的強大潛力，使得生成式AI能在無須大量標註資料下完成多種語言任務。

### 3. 生成對抗網路（GAN）與自動編碼器（VAE）

Goodfellow等人於2014年提出的生成對抗網路（GAN）【2】，是透過生成器與判別器間的對抗訓練來生成高擬真度的資料，廣泛應用於圖像合成、臉部模擬與風格轉換等領域。VAE（Variational Autoencoder）則由Kingma與Welling在2014年發表【5】，透過機率方法將資料映射至潛在空間進行重建與生成，可用於控制式圖像生成與潛在特徵分析。

| 類型  | 應用方向           | 對應論文                    |
| --- | -------------- | ----------------------- |
| GAN | 臉部生成、風格轉換、3D重建 | Goodfellow et al., 2014 |
| VAE | 特徵操控、風格探索、圖像插值 | Kingma & Welling, 2014  |

### 4. 多模態生成與Autoregressive Models

生成式模型現已拓展至多模態應用，包括由文字生成圖像（如DALL·E）、語音合成（如WaveNet）、影片預測與字幕生成等。這些模型多採用Autoregressive策略逐步生成內容，特別是在語音與自然語言處理任務上，透過先前輸出推測下一步，有效捕捉語意連貫性與上下文邏輯。

### 5. 實例應用：ChatGPT與GPT-4的語意理解

演講中以ChatGPT 3.5與GPT-4比較為例，突顯大型語言模型（LLM）在語意理解、邏輯推理與回應品質的提升。這些成果皆建立於Transformer與預訓練語言建模技術之上，使其能廣泛應用於教育輔助、客服對話、知識問答與程式撰寫等實務場景。

---

## 三、個人心得

這場演講讓我對生成式AI的技術歷程與應用潛力有更深入理解。從神經網路的演進到Transformer的橫空出世，再到各種生成模型的應用場景，體現AI在語言、視覺乃至創造力上的飛躍。我特別對GAN與VAE在圖像生成的彈性與真實度感到驚艷，也意識到生成式AI不僅是科技突破，更牽動著法律、教育與社會倫理的多方議題。對我而言，這場講座不只是技術性的啟發，更激發了我對未來AI研究的熱情與責任感。

---

## 四、關鍵字

Generative AI、Transformer、LSTM、GAN、VAE、Autoregressive Models、ChatGPT、GPT-3、GPT-4、Deep Learning、神經網路、Self-Attention、少樣本學習

---

## 五、參考文獻

1. Vaswani et al., “Attention is All You Need,” NeurIPS 2017.
2. Goodfellow et al., “Generative Adversarial Nets,” NeurIPS 2014.
3. Hochreiter & Schmidhuber, “Long Short-Term Memory,” Neural Computation, 1997.
4. Radford et al., “Language Models are Few-Shot Learners,” OpenAI 2020 (GPT-3).
5. Kingma & Welling, “Auto-Encoding Variational Bayes,” ICLR 2014.
