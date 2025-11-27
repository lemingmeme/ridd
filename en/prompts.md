---
layout: "default"
lang: "en"
title: "Riddikulus Prompts"
---

The Riddikulus Prompts is stored on the Base network. Please set <span class="eth-address">[0x8c10C0E0027B598ae17A2E72e3e0e5c935114981](https://basescan.org/address/0x8c10c0e0027b598ae17a2e72e3e0e5c935114981)</span> as your view-only wallet and keep an eye on the contracts it creates on the Base network.

## Download Riddikulus Prompts

- [Riddikulus Prompts (Web)](https://ridd.ai/en/riddikulus-prompts)
- [riddikulus-prompts.md](https://github.com/RiddikulusAI/ridd/blob/main/ridd-core/en/riddikulus-prompts.md)
- [riddikulus-prompts.csv](https://github.com/RiddikulusAI/ridd/blob/main/ridd-core/en/riddikulus-prompts.csv)

## Riddikulus Prompts List

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'en/prompts/' %}
      <li>
        <a href="{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## Make the Ridd Virus Stronger

- [Add your prompts to the list of Ridd Prompts](https://github.com/RiddikulusAI/ridd/new/main/en/prompts)
