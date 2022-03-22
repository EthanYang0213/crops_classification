# AIdea_農地作物現況調查影像辨識競賽
## 競賽介紹
農地作物現況調查可使用人員搭配相機於現地拍照紀錄，然而農地區域廣泛、我國之坵塊分割細碎且分佈零碎，所獲取之照片影像資料龐大，轉換為可用於管理操作之資訊，極度耗費人力、時間。AI技術對於影像判識工作近年已有長足之進步，適合導入農地作物現況調查之工作程序 ，加速農政單位獲取相關資訊。

目前雖然有完整的民生/工業/醫療等AI資料集，但在農業數據相對缺乏，故在未來AI智慧農業需求上，將需要投入大量的專業人力進行農業數據蒐集及分析作業；透過本競賽，將協助學生瞭解農業資料集及農產業影像辨識的應用需求，並培育學生應用AI進行農業領域影像辨識的經驗及技術能力。

本競賽資料來源為行政院農委會農業試驗所，影像均已由專家進行分類，包含13種作物及2種農地狀態之標註資訊。參賽隊伍需能使用AI正確辨識各影像之作物。

## 評估標準
評估方式採用Weighted-Precision(WP), 且各類別F1-score需大於0.7
![Untitled](https://user-images.githubusercontent.com/45745211/159399235-6b854dd3-2123-403c-8859-59443684c224.png)

## 資料說明
本次競賽包含13種作物及2種農地狀態之標註資訊。15個類別包括：香蕉、胡蘿蔔、玉米、火龍果、大蒜、芭樂、花生、鳳梨、南瓜、稻米、大豆、甘蔗、蕃茄、整地、淹水。各類別影像數量分別約2000至10000張不等，影像解析度最小為1280*720*，最大為4000**3000。

- 訓練集資料內容為作物全彩(RGB)影像，各類別以不同資料夾分別儲存，檔案夾名稱為類別名稱；測試集資料內容為作物全彩(RGB) 影像。
- 類別名稱為: banana, carrot, corn, dragonfruit, garlic, guava, peanut, pineapple, pumpkin, rice, soybean, sugarcane, tomato, bareland, inundated
- 訓練資料集至少80000張影像; 測試資料集約20000張影像。
- 總資料大小為156 g
