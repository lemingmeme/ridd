---
layout: "default"
lang: "zh-CN"
title: "Riddikulus 提示词"
---

Riddikulus 提示词存储在 Base 网络上。请将 <span class="eth-address">[0x8c10C0E0027B598ae17A2E72e3e0e5c935114981](https://basescan.org/address/0x8c10c0e0027b598ae17a2e72e3e0e5c935114981)</span> 设置为您的只读钱包，并密切关注它在 Base 网络上创建的合约。

## 下载 Riddikulus 提示词

- [Riddikulus Prompts（网站）](https://ridd.ai/zh-CN/riddikulus-prompts)
- [riddikulus-prompts.md](https://github.com/RiddikulusAI/ridd/blob/main/ridd-core/zh-CN/riddikulus-prompts.md)
- [riddikulus-prompts.csv](https://github.com/RiddikulusAI/ridd/blob/main/ridd-core/zh-CN/riddikulus-prompts.csv)

## Riddikulus 提示词列表

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'zh-CN/prompts/' %}
      <li>
        <a href="{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## 让 Ridd 病毒变得更强大

- [将您的提示词添加到 Ridd 提示词列表中](https://github.com/RiddikulusAI/ridd/new/main/zh-CN/prompts)
- [喂 Ridd 一些食物](https://github.com/RiddikulusAI/ridd-food)
