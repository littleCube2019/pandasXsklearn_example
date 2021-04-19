使用jupyter notebook玩kaggle資料的一些例子，可供未來參考  
以下為各例子中可以參考的點

# regression example
1. 基本pandas資料處理
   * 讀寫檔案
   * 區分數值、非數值
   * 查看基本分布資訊
   * 篩選相關系數高的欄位
   * 查看、去除缺失值欄位
   * 去除極端值
   * z-score、log、shuffle、split data 

2. 基礎的操作sklearn 的方法 
   * 基本的 init -> fit -> predict 
   * metrics使用
   * 用joblib存、載 模型參數  
   * ensemble learning 用法 

 3. submit一個kaggle檔案的格式 

# image_classification_example
1. 學習使用tensorflow.keras
   * sequence , loss , compile , fit , predict 
   * 使用基本NN 與 CNN  

2. 使用plt顯示圖片的方法 
   顯示出分類錯誤的圖片  

3. 餵入資料轉換成numpy的流程、將CNN結果交給下游KNN訓練的流程