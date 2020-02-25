---
title: F1 AFR联赛 S5赛季 A2组别 Round2 · 巴林站
description: AFR S5赛季A2组别 第二站巴林站落下帷幕, 恭喜赛点车队的SSS获得冠军; 恭喜ChevyVetteLove和silence banana登上领奖台.
---

{{ page.description }}

## 结果

{% include tables/AFR-S5-A2-R02-Bahrain-table.html %}

## 视频

<script type="text/javascript">
function bilibili(link) {
  document.getElementById('bilibili').src = link + '&high_quality=1&danmuku=1';
}
</script>
<ol class="video">
{% for item in site.data.videos.AFR-S5-A2-R02-Bahrain-video %}
  <li onclick="bilibili('{{ item.link }}')">
    {{ item.name }}
  </li>
{% endfor %}
</ol>

<iframe id="bilibili" src="{{ site.data.videos.AFR-S5-A2-R02-Bahrain-video[0].link }}&high_quality=1&danmaku=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" class="bilibili"> </iframe>

<h3 id="%E8%BD%A6%E8%BD%BD">车载</h3>
<p><a href="https://www.bilibili.com/video/av89554125">Lee25719(9--&gt;2)</a></p>
<p><a href="https://www.bilibili.com/video/av87666051">flamus(整活啦！花式白给集锦！)</a></p>
<p><a href="https://www.bilibili.com/video/av87670196">32(排位白给，正赛捡捡皮夹挺惬意)</a></p>

## 赛道

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/Flag_of_Bahrain.svg/510px-Flag_of_Bahrain.svg.png" alt="国旗">

## 判罚

{% include penalties/AFR-S5-A2-R02-Bahrain-penalty.md %}
