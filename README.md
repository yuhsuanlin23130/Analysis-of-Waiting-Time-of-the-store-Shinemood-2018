#### 說明
身為台大人，我們觀察到坐落於台大的小木屋鬆餅人潮川流不息，常有排隊情形。團隊查詢Google所測量的平日等待時間統計，平均為5.378分鐘，但依據經驗，真正的平均等待時間應該和Google的值有所出入。所以透過實地記錄每個時間點客人排隊時間，透過敘述統計分析與假設檢定，以統計角度推論是否能推翻5.378分鐘的排隊時間。
假設檢定結果，本次團隊蒐集資料所得之平均等待時間的95％信心水準區間，並未cover到Google所列之5.378分鐘▫固有足夠信心推論真正所需平均等待時間與Google的值有所出入。推測原因為Google僅利用GPS定位在該店的人潮，並不能準確推論為等待時間。

#### 執行環境
R + Rstudio

#### 目錄結構說明
* Google record為Google所顯示之每個時段排隊人數之敘述統計。
* record.xlsx為團隊所蒐集之原始資料。
* descriptive_statistics.csv為團隊蒐集資料敘述統計。
* analysis1.Rmd/analysis1.nb為團隊蒐集資料敘述統計之視覺化與分析。