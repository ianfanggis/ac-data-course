### 專案目的
- Collaborative filtering
-- User-based collaborative filtering
-- Item-based collaborative filtering
-- 套件 surprise 實作 collaborative filtering
### 工具
- python, colab, pandas, numpy, surprise

### 基本資料描述
- 訓練資料:2000.01.10-2018.09.01
- 測試資料:2018.09.01-2018.09.30
- 使用者列表

### 資料整理
1. 此次針對ratings資料作處理
2. 保留每位使用者最新一則評論
3. 因資料量過大，進而只保留2017-09-01後的資料
4. 保留N >3的使用者


### 邏輯
1. 建立similarity Matrix
2. 以similarity Matrix找出與 item_based, user_based相似的產品，而被推薦人還沒買的產品


### 推薦分數
1. User-based : 0.0
2. Item-based : 0.0
3. surprise : 0.001694915254237288

### 是否成功
- 成功





