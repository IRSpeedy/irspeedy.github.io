---
layout: default
title: "تماس با IRSpeedy"
description: "تماس با IRSpeedy"
---


<p class="text-center mb-4">
    <img src="{{ '/assets/images/IRSPEEDY-L.webp' | relative_url }}" alt="IRSPEEDY" width="293" height="300">
</p>

<p>برای ارتباط با ما می‌توانید از طریق شبکه های اجتماعی متنوع ما اقدام نمایید.</p>
<p>همچنین پس از خرید و فعال سازی سرویس امکان ارسال تیکت از طریق پنل کاربری برای شما وجود خواهد داشت.</p>
<h6>شبکه‌های اجتماعی ما</h6>
<div class="social mb-4">
    {% for social in site.data.socials %}
    <a class="btn btn-light{{ social.class }}" href="{{ social.link }}" title="{{ social.title }}">
    <span class="{{ social.icon}}"></span> <span>{{ social.title }}</span>
    </a>
    {% endfor %}
</div>
<h6>ارتباط با پشتیبانی</h6>
<div class="supports mb-4">
    {% for support in site.data.supports %}
    <a class="btn btn-light{{ support.class }}" href="{{ support.link }}" title="{{ support.title }}">
    <span class="{{ support.icon}}"></span> <span>{{ support.title }}</span>
    </a>
    {% endfor %}
</div>