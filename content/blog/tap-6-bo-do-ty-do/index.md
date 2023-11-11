---
title: "Tập 6: Những bộ đồ tỷ đô"
date: "2023-11-10T13:58:09+07:00"
draft: false
comments: false
socialShare: true
toc: false
author: Nguyen Talk
images:
  - ./blog/tap-6-bo-do-ty-do/6.webp
---

<div class="embed-tabs">
  <input class="embed-input" name="tabs-6" type="radio" id="embed-tab-D_oYP9oyTeM" checked="checked" />
  <label class="embed-label" for="embed-tab-D_oYP9oyTeM">
    <img src="/youtube-20x20.png" alt="Icon" style="margin-right: 10px; ">
    <p>Youtube</p>
  </label>
  <div class="embed-panel">
    {{< youtube id="D_oYP9oyTeM" >}}
  </div>
  <input class="embed-input" name="tabs-6" type="radio" id="embed-tab-6eaYnqR00YlGy6EhhswKuT" />
  <label class="embed-label" for="embed-tab-6eaYnqR00YlGy6EhhswKuT">
    <img src="/spotify-20x20.png" alt="Icon" style="margin-right: 10px; ">
    <p>Spotify</p>
  </label>
  <div class="embed-panel">
    {{< spotify type="episode" id="6eaYnqR00YlGy6EhhswKuT" width="100%" height="232" >}}
  </div>
  <input class="embed-input" name="tabs-6" type="radio" id="embed-tab-1000634270274"/>
  <label class="embed-label" for="embed-tab-1000634270274">
    <img src="/apple-podcast-20x20.png" alt="Icon" style="margin-right: 10px; ">
    <p>Apple</p>
  </label>
  <div class="embed-panel">
    {{< apple-podcast src="https://embed.podcasts.apple.com/vn/podcast/6-nh%E1%BB%AFng-b%E1%BB%99-%C4%91%E1%BB%93-t%E1%BB%B7-%C4%91%C3%B4/id1703803404?i=1000634270274" >}}
  </div>
</div>

Podcast kỳ này là về ngành dệt may qua góc nhìn của chị Kim - Merchandise Manager tại Tập Đoàn PPJ.<br>
<!--more-->

Chị Kim sẽ kể cho chúng mình nghe về công việc của Người theo dõi đơn hàng (Merchadiser) - 1 công việc (theo Nguyên là) khó nhằn và cần ít nhất 3 năm để làm quen đó. Ngoài ra, qua mô hình SWOT, chúng ta cũng sẽ hiểu rõ hơn về tình hình hiện tại của ngành dệt may tại Việt Nam.<br>

Hãy follow và theo dõi các tập mới nhất của Nguyen Talk nhé!

<script>
  document.addEventListener("DOMContentLoaded", function () {
    const platformSwitcher = document.getElementById("platform-switcher");

    platformSwitcher.addEventListener("click", function (event) {
      if (event.target.dataset.platform) {
        const platform = event.target.dataset.platform;

        // Hide all iframes initially
        const iframes = document.querySelectorAll('[id$="-embed"]');
        iframes.forEach((iframe) => {
          iframe.style.display = 'none';
        });

        // Show the selected iframe
        const selectedIframe = document.getElementById(`${platform}-embed`);
        if (selectedIframe) {
          selectedIframe.style.display = 'block';
        }
      }
    });
  });
</script>
