---
layout: default
---

# 📚 工程專題學習總整理

這是一個有關工程研究報告的總整理

<style>
    /* 強制隱藏左側邊欄，讓內容滿版 */
    @media screen and (min-width: 64em) {
        section { width: 100% !important; max-width: 900px !important; margin: 0 auto !important; }
        aside { display: none !important; }
    }
    
    .card-container {
        display: flex;
        gap: 20px;
        margin-top: 20px;
        flex-wrap: wrap;
    }
    .card {
        flex: 1;
        min-width: 280px;
        padding: 25px;
        border: 1px solid #e0e0e0;
        border-radius: 12px;
        background-color: #ffffff;
        text-align: center;
        transition: transform 0.2s, box-shadow 0.2s;
        text-decoration: none !important;
        color: #333 !important;
        display: block;
    }
    .card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        background-color: #f8fbff;
    }
    .card-title {
        display: block;
        font-size: 1.5em;
        font-weight: bold;
        color: #007bff;
        margin-bottom: 8px;
    }
    .card-desc {
        display: block;
        font-size: 1em;
        color: #666;
        margin-bottom: 20px;
    }
    .btn-start {
        display: inline-block;
        padding: 10px 30px;
        background-color: #007bff;
        color: white !important;
        border-radius: 6px;
        font-weight: bold;
        text-decoration: none !important;
    }
</style>

<div class="card-container">

<a href="mid_report" class="card">
    <span class="card-title">📊 期中報告</span>
    <span class="card-desc">matlab創意主題</span>
    <span class="btn-start">開始學習</span>
</a>

<a href="last_report" class="card">
    <span class="card-title">☁️ 期末報告</span>
    <span class="card-desc">不同卷積神經訓練AI</span>
    <span class="btn-start">開始學習</span>
</a>

</div>

---
