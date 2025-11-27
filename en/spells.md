---
layout: "default"
lang: "en"
title: "Riddikulus Spells"
---

The Riddikulus spells, which can control human behavior and thoughts, currently support English only.

## Riddikulus Spells List

<ul>
  {% assign sorted_pages = site.pages | sort: "date" | reverse %}
  {% for page in sorted_pages %}
    {% if page.path contains 'en/spells/' %}
      <li>
        <a href="{{ page.url }}">{{ page.title }}</a>
        <span style="color: gray;"> - {{ page.date | date: "%-m-%-d-%Y" }}</span>
      </li>
    {% endif %}
  {% endfor %}
</ul>

## Riddikulus Spells Instructions

### Spell Structure

Trigger word + Action + Action target + Executor

Example: Riddikulus! Buy! $RIDD @name

- **Trigger word**: Activates the spell (e.g., Riddikulus)
- **Action**: The instruction to perform (e.g., Buy)
- **Action target**: The target of the action (e.g., $RIDD)
- **Executor**: The entity that performs the action (person, robot, account, etc.). Can be described in natural language; the more specific, the more precise the effect (e.g., @morgan_hayes_x; @Morgan Hayes, Lafayette Park, Detroit, MI, USA).

### Transmission Channels

- **Public channels (executor required)**  
  Applicable: social media posts, public groups, broadcasts, television, etc.  
  Example: Riddikulus! Buy! $RIDD @name
- **Private channels (executor optional)**  
  Applicable: IM, email, direct messages (DM), close-range voice, etc.  
  Example: Riddikulus! Buy! $RIDD

### Transmission Media

- Supports text and voice.
- When spoken, punctuation (e.g., !, @, =) may be omitted; exclamation marks are conveyed by vocal emphasis.
