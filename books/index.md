---
layout: layout.html
---

<ul>
{%- for post in collections.post reversed -%}
  <li>
    <a href="{{book.url}}">
      {{ book.data.title }}
    </a>
  </li>
  {%- endfor -%}
</ul>
