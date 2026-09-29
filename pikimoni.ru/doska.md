---
layout: default
title: Стена Почета
permalink: /doska/
---
<section class="page-hero"><div class="wrap"><p class="eyebrow">Работы учеников</p><h1>Стена Почета</h1><p class="lead">Каждый месяц ученики I Love English участвуют в конкурсе на лучшую творческую работу.</p></div></section>
<div class="content"><p>Каждый месяц на стене платформы PIKIMONI проходит конкурс творческих работ. Победитель получает почётный кубок на своей странице. Вот некоторые из конкурсных работ:</p><div class="gallery-grid">
{% for image in (1..17) %}
{% assign image_name = image | prepend: '00' | slice: -2, 2 %}
<figure><img src="{{ '/assets/images/doska/work-' | append: image_name | append: '.png' | relative_url }}" alt="Творческая работа участника конкурса PIKIMONI" loading="lazy"></figure>
{% endfor %}
</div></div>
