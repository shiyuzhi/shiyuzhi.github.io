---
layout: default
title: Yori的個人網站
description: 歡迎來到我的個人網站
---

<main>
    <section id="about">
        <img src="/images/bear.png" alt="王熊熊" />
        <p>頭像是胸毛公寓的王熊熊，作者為 <a href="https://www.instagram.com/mdzz3310/" target="_blank">mdzz3310</a>。</p>
        <p>Hi, I am Yori。這是我的個人網站。</p>
        <p>最近颱風天，天氣不錯，希望可以保持這樣的運勢。</p>
        <p>最近更新時間: 2024/10/31</p>
    </section>        
    <section id="articles">
        <h2>最近的文章</h2>
        <div class="article-container">
            <div class="article-preview" onclick="window.open('https://example.com/news1', '_blank');">
                <h3>新聞標題1</h3>
                <p>新聞摘要1...</p>
            </div>
            <div class="article-preview" onclick="window.open('https://example.com/news2', '_blank');">
                <h3>新聞標題2</h3>
                <p>新聞摘要2...</p>
            </div>
            <div class="article-preview" onclick="window.open('https://example.com/news3', '_blank');">
                <h3>新聞標題3</h3>
                <p>新聞摘要3...</p>
            </div>
            <div class="article-preview" onclick="window.open('https://example.com/news4', '_blank');">
                <h3>新聞標題4</h3>
                <p>新聞摘要4...</p>
            </div>
        </div>
    </section>
</main>

<script>
    function toggleMenu() {
        var navLinks = document.getElementById("nav-links"); // 獲取導覽列
        navLinks.classList.toggle("show"); // 切換顯示
    }
</script>


