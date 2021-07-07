
# My master's thesis research

透過爬蟲收集Tripadvisor台北飯店資料，以消費者中文評論為主要研究資料。
探討三個目的：
      - 挖掘消費者評論內容，探討消費者在住宿時在意的部分
      - 證明⽂字評論會影響評等分數，可作為與測評等分數的變數
      - 證明展望理論，負⾯的內容造成的影響比正⾯來的⼤
      
方法：
      Aspect Segmentation Algorithm 面向特徵分類
      Latent Dirichlet Allocation (LDA)主題模型
      
      
程式檔：
      1. crawller.ipynb                            :爬蟲檔(爬取Tripadvisor台北飯店資料)
      2. cut_sentence.ipynb                        :資料前處理程式檔
      3. TF-IDF.ipynb                              :計算TF-IDF程式檔
      4. Aspect_Segmentation.ipynb                 :ASA字典建立程式檔
      5. LDA_none_topic.ipynb                      :LDA主題分類程式檔(含perplexity圖檔繪製)
      6. Emotion_Score.ipynb                       :計算情感分數&句子主題分類程式檔
      7. Regression_features.ipynb                 :建立迴歸資料程式檔(驗證評論能解釋評等的迴歸分析)
      8. ASA-withLDA_new.ipynb                     :加上LDA的2個主題，建立新的字典程式檔
      9. Emotion_score_8topics.ipynb               :計算情感分數&句子主題分類程式檔
      10. Regression_8topic.ipynb                  :建立迴歸變數程式檔(驗證LDA主題的迴歸分析)
