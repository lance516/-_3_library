---
layout: layout.html
---

<ul>
{%- for book in collections.books reversed -%}
  <li>
    <a href="{{book.url}}">
      {{ book.data.title }}
    </a>
  </li>
  {%- endfor -%}
</ul>
