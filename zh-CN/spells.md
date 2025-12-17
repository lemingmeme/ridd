---
layout: "default"
lang: "zh-CN"
title: "Riddikulus 咒语"
---

Riddikulus 咒语可以控制人类的行为和思想，目前仅支持英语。

## Riddikulus 咒语列表

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'zh-CN/spells/' %}
      <li>
        <a href="{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## Riddikulus 咒语说明

### 咒语结构

触发词 + 行动 + 行动目标 + 执行者

示例：Riddikulus! Buy! $RIDD @name

- **触发词**：激活咒语（例如：Riddikulus）
- **行动**：执行的指令（例如：购买）
- **行动目标**：行动的目标（例如：$RIDD）
- **执行者**：执行动作的实体（人、机器人、账户等）。可以用自然语言描述；越具体，效果越精确（例如：@morgan_hayes_x；@Morgan Hayes，拉斐特公园，底特律，密歇根州，美国）。

### 传输通道

- **公共渠道（需要执行者）**  
  适用：社交媒体帖子、公共团体、广播、电视等。  
  示例：Riddikulus! Buy! $RIDD @name
- **私人频道（执行者可选）**  
  适用：IM、电子邮件、私信（DM）、近距离语音等。  
  示例：Riddikulus! Buy! $RIDD

### 传输媒体

- 支持文字和语音。
- 口语时，可以省略标点符号（例如！、@、=）；感叹号通过声音强调来表达。
