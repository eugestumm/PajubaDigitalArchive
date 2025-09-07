---
title: Pajuba-English Glossary
layout: page
permalink: /pajuba_english.html
---
# Pajubá-English Glossary

This section offers a lexical sample in Pajubá along with their English counterpart.

<ul>
  {% for item in site.data.pajuba %}
    <li><strong>{{ item.pajuba_word | strip }}</strong>: {{ item.english_equivalent | strip }}</li>
  {% endfor %}
</ul>
