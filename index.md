---
layout: home
title: 林浩唐技術筆記
author_profile: false
---

<section class="hero-panel">
  <p class="hero-panel__eyebrow">SOFTWARE ENGINEERING · MACHINE VISION</p>
  <h1>讓複雜技術，真正落地</h1>
  <p class="hero-panel__lead">我是林浩唐，一名專注於 C#、WPF、影像演算法與自動化設備整合的軟體工程師。這裡記錄從系統設計到現場實作的經驗與思考。</p>
  <div class="hero-panel__actions">
    <a class="button button--primary" href="#articles">瀏覽技術文章</a>
    <a class="button button--secondary" href="#contact">與我聯絡</a>
  </div>
</section>

<section class="expertise-section" aria-labelledby="expertise-title">
  <div class="section-heading">
    <p class="section-heading__eyebrow">EXPERTISE</p>
    <h2 id="expertise-title">專業領域</h2>
  </div>
  <div class="expertise-grid">
    <article class="expertise-card">
      <span class="expertise-card__index">01</span>
      <h3>機器視覺與 AI</h3>
      <p>AI 檢測、分類、影像演算法，以及半導體 AOI 系統整合。</p>
    </article>
    <article class="expertise-card">
      <span class="expertise-card__index">02</span>
      <h3>精密成像與量測</h3>
      <p>顯微鏡自動化、3D 影像處理、光學量測與高速飛拍。</p>
    </article>
    <article class="expertise-card">
      <span class="expertise-card__index">03</span>
      <h3>C# 軟體架構</h3>
      <p>WPF、MVVM、資料結構與設備控制軟體的架構設計。</p>
    </article>
  </div>
</section>

<section id="articles" class="articles-section" aria-labelledby="articles-title">
  <div class="section-heading">
    <p class="section-heading__eyebrow">FIELD NOTES</p>
    <h2 id="articles-title">精選技術文章</h2>
    <p>來自醫療、自動化、科研與半導體設備開發現場的實作整理。</p>
  </div>
  <div class="article-grid">
    <a class="article-card" href="{{ '/posts/AIDetect01.html' | relative_url }}">
      <span class="article-card__tag">AI · MACHINE VISION</span>
      <h3>AI 視覺影像系統設計要點</h3>
      <p>從 Segmentation、Detection 到 Classification，整理視覺系統設計的核心觀念。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
    <a class="article-card" href="{{ '/posts/LightSheet01.html' | relative_url }}">
      <span class="article-card__tag">MICROSCOPY</span>
      <h3>層光顯微術成像系統的設計原則與技術挑戰</h3>
      <p>探討顯微成像系統在控制、影像與設備整合上的實務考量。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
    <a class="article-card" href="{{ '/posts/OpticalProfiler01.html' | relative_url }}">
      <span class="article-card__tag">3D METROLOGY</span>
      <h3>3D 量測設備整合應用：雷射共軛焦</h3>
      <p>從設備整合角度理解 3D 光學量測的應用與技術重點。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
    <a class="article-card" href="{{ '/posts/MotionPhotography01.html' | relative_url }}">
      <span class="article-card__tag">SEMICONDUCTOR AOI</span>
      <h3>高倍晶圓飛拍檢測系統的挑戰與解決方案</h3>
      <p>分析高速運動、成像品質與檢測效率之間的工程取捨。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
    <a class="article-card" href="{{ '/posts/MotionPhotography02.html' | relative_url }}">
      <span class="article-card__tag">MOTION CONTROL</span>
      <h3>飛拍檢測系統相機與運動速度</h3>
      <p>整理相機參數、平台速度與影像品質之間的關聯。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
    <a class="article-card" href="{{ '/posts/MedicalAutomation01.html' | relative_url }}">
      <span class="article-card__tag">MEDICAL AUTOMATION</span>
      <h3>醫療自動化的困難與挑戰</h3>
      <p>從可靠性、流程與法規思維看醫療自動化設備的開發難題。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
    <a class="article-card" href="{{ '/posts/RxAndEvent.html' | relative_url }}">
      <span class="article-card__tag">SOFTWARE DESIGN</span>
      <h3>訂閱與事件的差異和適用場景</h3>
      <p>釐清兩種訊息傳遞方式的特色，以及架構設計時的選擇依據。</p>
      <span class="article-card__link">閱讀文章 →</span>
    </a>
  </div>
</section>

<section id="contact" class="contact-section" aria-labelledby="contact-title">
  <div class="section-heading">
    <p class="section-heading__eyebrow">GET IN TOUCH</p>
    <h2 id="contact-title">傳送訊息給我</h2>
    <p>想交流技術、討論合作或提供建議？歡迎留下訊息，我會透過你填寫的 Email 回覆。</p>
  </div>

<form class="contact-form" action="https://formsubmit.co/matt121031231@gmail.com" method="POST">
  <input type="hidden" name="_subject" value="HaoTangPages 網站的新訊息">
  <input type="hidden" name="_template" value="table">
  <input type="hidden" name="_next" value="https://haotang0611.github.io/HaoTangPages/thanks/">
  <input type="text" name="_honey" class="contact-form__honey" tabindex="-1" autocomplete="off">

  <div class="contact-form__field">
    <label for="contact-name">名稱</label>
    <input id="contact-name" name="名稱" type="text" autocomplete="name" maxlength="80" required>
  </div>

  <div class="contact-form__field">
    <label for="contact-email">Email</label>
    <input id="contact-email" name="email" type="email" autocomplete="email" maxlength="254" required>
  </div>

  <div class="contact-form__field">
    <label for="contact-message">內容</label>
    <textarea id="contact-message" name="內容" rows="7" maxlength="3000" required></textarea>
  </div>

  <button type="submit">傳送訊息</button>
</form>
</section>

