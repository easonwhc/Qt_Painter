# 多人小畫家應用 (Qt Painter)

這是一個使用 Qt 框架實現的小畫家應用，允許用戶在畫布上自由繪畫，並提供顏色選擇、畫筆大小調整、保存和載入等功能，並且支持多人連線。

### 組員:
- 李偉澄
- 陳仕育
- 翁浩宸


## 項目目標
- 在畫布上自由繪圖。
- 支援顏色選擇和畫筆大小調整。
- 支援清空畫布和保存畫布內容。
- 載入先前保存的圖片。
- 多人連線功能。

## 功能介紹

### 1. 畫布區域
- 可以在畫布區域內繪製線條、圓形、自由形狀等。
- 使用滑鼠拖動進行繪畫。

### 2. 顏色選擇
- 可以點擊顏色選擇器來選擇畫筆顏色。
- 預設顏色為黑色。

### 3. 畫筆大小調整
- 提供一個滑動條 (`QSlider`) 讓用戶調整畫筆大小。
- 畫筆大小可以動態調整。

### 4. 保存和載入
- 可以將畫布內容保存為 PNG 文件。
- 可以載入先前保存的圖像並在其上繪畫。

### 5. 多人連線
- 提供1-2個使用者能夠共同編輯畫布。
