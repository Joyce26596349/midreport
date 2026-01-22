---
layout: default
---

<style>
    /* 1. 徹底隱藏右側側邊欄與頁尾資訊 */
    aside#sidebar, footer { display: none !important; }
    
    /* 2. 讓主內容區域滿版，解決右邊空洞問題 */
    section#main_content { 
        width: 100% !important; 
        max-width: 1000px !important; 
        margin: 0 auto !important; 
        float: none !important; 
    }

    /* 3. 按鈕容器：改為 Flex 並排 */
    .card-container {
        display: flex;
        gap: 20px;
        margin-top: 30px;
        flex-wrap: wrap; /* 手機版會自動換行 */
    }

    /* 4. 按鈕卡片樣式 */
    .card {
        flex: 1; /* 平分寬度 */
        min-width: 300px;
        padding: 30px;
        border: 1px solid #e1e4e8;
        border-radius: 12px;
        background-color: #ffffff;
        text-align: center;
        text-decoration: none !important;
        transition: transform 0.2s, box-shadow 0.2s;
        box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        color: #24292e !important;
    }
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 12px 20px rgba(0,0,0,0.1);
    }
    .card-title { display: block; font-size: 1.6em; font-weight: bold; color: #007bff; margin-bottom: 10px; }
    .card-desc { display: block; font-size: 1em; color: #586069; margin-bottom: 25px; min-height: 3em; }
    .btn-ui {
        display: inline-block;
        padding: 10px 40px;
        background-color: #007bff;
        color: white !important;
        border-radius: 6px;
        font-weight: bold;
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
