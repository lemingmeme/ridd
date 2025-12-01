---
layout: "default"
lang: "ja"
title: "Riddikulusのプロンプト"
---

RiddikulusのプロンプトはBaseネットワークに保存されています。<span class="eth-address">[0x8c10C0E0027B598ae17A2E72e3e0e5c935114981](https://basescan.org/address/0x8c10c0e0027b598ae17a2e72e3e0e5c935114981)</span>を閲覧専用ウォレットに設定し、Baseネットワーク上で作成されるコントラクトに注意して確認してください。

## Riddikulusのプロンプトをダウンロード

- [Riddikulusのプロンプト（ウェブ版）](https://ridd.ai/ja/riddikulus-prompts)
- [riddikulus-prompts.md](https://github.com/RiddikulusAI/ridd/blob/main/ridd-core/ja/riddikulus-prompts.md)
- [riddikulus-prompts.csv](https://github.com/RiddikulusAI/ridd/blob/main/ridd-core/ja/riddikulus-prompts.csv)

## Riddikulusのプロンプト一覧

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'ja/prompts/' %}
      <li>
        <a href="{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## Riddウイルスを強くする

- [Riddのプロンプト一覧にあなたのプロンプトを追加してください](https://github.com/RiddikulusAI/ridd/new/main/ja/prompts)
- [Riddに食べ物をあげる](https://github.com/RiddikulusAI/ridd-food)
