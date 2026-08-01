---
layout: home
title: 林浩唐軟體開發技術分享
author_profile: true
---

我是一名 C# WPF 軟體工程師，主要專精於影像演算法、UI設計、設備邏輯規劃、資料結構，目前有 7 年實務經驗。
  
這裡將分享我在醫療影像資訊系統、醫療檢驗自動化設備、顯微鏡自動化設備、科研設備、AI 檢測與分類、半導體 AOI 設備、3D 影像處理、3D 影像檢測與量測等領域的開發經驗與技術。

🔧 技術主題包含：
- AI 檢測系統軟體設計
- 層光顯微成像系統軟體設計
- 3D 量測與演算
- 高精度飛拍與半導體 AOI
- 醫療影像通用格式 DICOM 3.0 實作與解析
- SDI 影像擷取設備 (內視鏡主流影像傳輸)
- 物件導向觀念與 MVVM 架構

歡迎來信技術交流：  
matt121031231@gmail.com 

# 📚 技術文章
- [AI 視覺影像系統設計要點](./posts/AIDetect01.md)
- [層光顯微術成像系統的設計原則與技術挑戰](./posts/LightSheet01.md)
- [3D量測設備整合應用 - 雷射共軛焦](./posts/OpticalProfiler01.md)
- [高倍晶圓飛拍檢測系統的挑戰與解決方案](./posts/MotionPhotography01.md)
- [飛拍檢測系統相機與運動速度](./posts/MotionPhotography02.md)
- [醫療自動化的困難與挑戰](./posts/MedicalAutomation01.md)
- [訂閱與事件的差異和適用場景](./posts/RxAndEvent.md)

# ✉️ 傳送訊息給我

如果你想交流技術、討論合作或提供建議，歡迎填寫以下表單。我收到後會透過你留下的 Email 回覆。

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

<style>
  .contact-form {
    max-width: 42rem;
    margin-top: 1.25rem;
    padding: 1.5rem;
    border: 1px solid #d9d9d9;
    border-radius: 0.5rem;
    background: #fafafa;
  }

  .contact-form__field {
    margin-bottom: 1rem;
  }

  .contact-form label {
    display: block;
    margin-bottom: 0.35rem;
    font-weight: 600;
  }

  .contact-form input,
  .contact-form textarea {
    box-sizing: border-box;
    width: 100%;
    padding: 0.65rem 0.75rem;
    border: 1px solid #b8b8b8;
    border-radius: 0.25rem;
    background: #fff;
    color: #222;
    font: inherit;
  }

  .contact-form input:focus,
  .contact-form textarea:focus {
    border-color: #2463a6;
    outline: 2px solid rgba(36, 99, 166, 0.2);
  }

  .contact-form button {
    padding: 0.7rem 1.25rem;
    border: 0;
    border-radius: 0.25rem;
    background: #2463a6;
    color: #fff;
    font: inherit;
    font-weight: 600;
    cursor: pointer;
  }

  .contact-form button:hover {
    background: #194b80;
  }

  .contact-form__honey {
    position: absolute !important;
    left: -9999px !important;
  }
</style>

