---
layout: default
---

<style>
    /* 1. 隱藏右側欄、頁尾與主題預設的下載按鈕 */
    aside#sidebar, footer, .view { 
        display: none !important; 
    }
    
    /* 2. 讓主內容區域滿版顯示，解決截圖中右側空白的問題 */
    section#main_content { 
        width: 100% !important; 
        max-width: 1100px !important; 
        margin: 0 auto !important; 
        float: none !important; 
    }

    /* 3. 設定按鈕容器為橫向並排 (Flexbox) */
    .card-container {
        display: flex;
        gap: 20px;            /* 兩個卡片之間的間距 */
        margin: 40px 0;
        flex-wrap: nowrap;     /* 強制不換行，確保橫向並排 */
        align-items: stretch;  /* 讓兩個卡片高度一致 */
    }

    /* 4. 重新定義卡片樣式 */
    .card {
        flex: 1;               /* 平分寬度 */
        padding: 30px 20px;
        border: 1px solid #e1e4e8;
        border-radius: 12px;
        background-color: #ffffff;
        text-align: center;
        text-decoration: none !important;
        display: flex;
        flex-direction: column;
        justify-content: space-between; /* 讓內容與按鈕上下分開 */
        transition: transform 0.2s, box-shadow 0.2s;
        box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        color: #24292e !important;
    }
    
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 12px 24px rgba(0,0,0,0.15);
    }

    .card-title { 
        font-size: 1.4em; 
        font-weight: bold; 
        color: #007bff; 
        margin-bottom: 15px;
        display: block;
    }
    
    .card-desc { 
        font-size: 0.95em; 
        color: #586069; 
        margin-bottom: 25px; 
        line-height: 1.6;
        flex-grow: 1; /* 自動撐開空間 */
    }

    .btn-ui {
        padding: 12px 0;
        width: 80%;
        margin: 0 auto;
        background-color: #007bff;
        color: white !important;
        border-radius: 6px;
        font-weight: bold;
        text-decoration: none !important;
    }
</style>

# 📚 工程專題學習總整理

<div class="card-container">

<a href="mid_report" class="card">
    <span class="card-title">📊 期中報告</span>
    <span class="card-desc">結合了matlab和生程式AI的運用，並適用在實體創意主題上</span>
    <span class="btn-start">開啟報告</span>
</a>

<a href="last_report" class="card">
    <span class="card-title">☁️ 期末報告</span>
    <span class="card-desc">使用 matlab 中 deep network designer 判斷出圖片中天空中不同雲朵的類型 </span>
    <span class="btn-start">開啟報告</span>
</a>

</div>
