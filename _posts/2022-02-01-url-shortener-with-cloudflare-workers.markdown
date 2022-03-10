---
layout: post
title: 'Rút Gọn URL Miễn Phí Với Cloudflare Workers'
date: 2022-02-01 08:00:00 +0700
categories: cloudflare workers
---

<html lang="en">
<head>
  <meta charset="utf-8">
    <link rel="canonical" href="https://huong-dan.github.io/url-shortener-cloudflare-workers/">
    <meta name="viewport" content="width=device-width,minimum-scale=1,initial-scale=1">
    <meta name='description' content='Hướng dẫn sử dụng Cloudflare Workers chi tiết để rút gọn url tùy chỉnh miễn phí 100%.'>

<script type="text/javascript">
    (function(c,l,a,r,i,t,y){
        c[a]=c[a]||function(){(c[a].q=c[a].q||[]).push(arguments)};
        t=l.createElement(r);t.async=1;t.src="https://www.clarity.ms/tag/"+i;
        y=l.getElementsByTagName(r)[0];y.parentNode.insertBefore(t,y);
    })(window, document, "clarity", "script", "amc2apgl8x");

  </script>
  {% seo %}
  </head>
<div class="content card">
<h2 id="steps">Các Bước Thực Hiện</h2>
<li>Sau khi đã tạo tài khoản Cloudflare, vào mục <a href="https://dash.cloudflare.com/sign-up/workers">Workers</a>.</li>
<li>Bạn chọn cho mình một subdomain, chọn gói miễn phí.</li>
<li>Sau đó, chọn Create a Service.</li>
<img src="/assets/img/2022-02-01-url-shortener-with-cloudflare-workers/img1.png" alt="Create a Service button"   />
<li>Đặt tên theo ý thích.</li>
<img src="/assets/img/2022-02-01-url-shortener-with-cloudflare-workers/img2.png" alt="Service name"  /> 
<li>Sau khi đã hoàn tất việc tạo một Worker (Service), bạn nhấn Quick edit ở trang quản lý Worker.
<img src="/assets/img/2022-02-01-url-shortener-with-cloudflare-workers/img3.png" alt="Quick edit button"   />
<li>Rồi dán vào đoạn mã dưới đây.</li>
<script src="https://gist.github.com/chupper100/401fef99f2e8200d021b2518c1e49b44.js" width="300" height="100"></script>
<li>Sau đó, nhấn <strong>Save and Deploy</strong> và thưởng thức thành quả:)</li>
<h2 id="resources">Resources</h2>
<li>Nguồn tham khảo: <a href="https://lucjan.medium.com/free-url-shortener-with-cloudflare-workers-125eaf87b1ec">Lucjan Suski</a></li>
<li><a href="https://developers.cloudflare.com/workers/examples/bulk-redirects">Docs/Bulk redirects </a></li>
<div class="card discussion">
    <script src="https://giscus.app/client.js"
    data-repo="Huong-Dan/huong-dan.github.io"
    data-repo-id="R_kgDOG1g2lQ"
    data-mapping="number"
    data-term="11"
    data-reactions-enabled="1"
    data-emit-metadata="0"
    data-input-position="top"
    data-theme="dark"
    data-lang="en"
    crossorigin="anonymous"
    async>
</script>
</div>
<script>
  document.querySelectorAll('img').forEach(e => {
    e.addEventListener("click", function(){
      window.location.href = e.src; 
    })
  })
</script>
