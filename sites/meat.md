---
layout: default
title: "프레시원미트"
permalink: /meat
image0: img/meat_info_210630.png
image1: img/meat_info_210701.png
image: img/meat.png
---

# {{ page.title }} 소개

인천 본점 : 인천 계양구 아나지로 495

남양주 분점 : 경기 남양주시 진접읍 경복대로272번길 27

대구 분점 : 대구 서구 국채보상로3길 25

# 공시 자료

{% if page.image0 %}
<p style="text-align: right; font-size: 12px;">게시일: 2021-6-30 14:22</p>
![그림00]({{ page.image1 }})
<hr/>
{% endif %}
 
{% if page.image1 %}
<p style="text-align: right; font-size: 12px;">게시일: 2021-7-01 08:57</p>
![그림01]({{ page.image0 }})
<hr/>
{% endif %}

{% if page.image %}
![그림00]({{ page.image }})
{% endif %}
