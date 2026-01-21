---
layout: default
---

<style>
    /* 1. 強制讓內容滿版並隱藏左側邊欄 */
    #sidebar, .sidebar, aside { display: none !important; }
    #content, section, .wrapper { 
        width: 100% !important; 
        max-width: 900px !important; 
        margin: 0 auto !important; 
        float: none !important; 
    }

    /* 2. 卡片容器設定 */
    .card-container {
        display: block;
        width: 100%;
        margin-top: 20px;
    }

    /* 3. 卡片外框與按鈕一體化 */
    .card {
        display: block;
        border: 1px solid #e0e0e0;
        border-radius: 12px;
        padding: 25px;
        margin-bottom: 20px;
        text-align: center;
        text-decoration: none !important;
        background-color: #ffffff;
        transition: 0.2s;
        color: #333 !important;
    }
    .card:hover {
        box-shadow: 0 8px 15px rgba(0,0,0,0.1);
        background-color: #f9fbff;
    }

    /* 4. 文字與按鈕樣式 */
    .card-title { display: block; font-size: 1.6em; font-weight: bold; color: #007bff; margin-bottom: 5px; }
    .card-desc { display: block; font-size: 1em; color: #666; margin-bottom: 15px; }
    .btn-ui {
        display: inline-block;
        padding: 8px 30px;
        background-color: #007bff;
        color: white !important;
        border-radius: 5px;
        font-weight: bold;
    }
</style>

# 📚 工程專題學習總整理

這是一個有關工程研究報告的總整理

<div class="card-container">

<a href="mid_report" class="card">
<span class="card-title">📊 期中報告</span>
<span class="card-desc">matlab創意主題</span>
<span class="btn-ui">開始學習</span>
</a>

<a href="last_report" class="card">
<span class="card-title">☁️ 期末報告</span>
<span class="card-desc">不同卷積神經訓練AI</span>
<span class="btn-ui">開始學習</span>
</a>

</div>
