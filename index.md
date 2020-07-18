---
layout: layout.html
---

<ul>
{%- for book in collections.book reversed -%}
  <li>
    <a href="{{book.url}}">
      {{ book.data.title }}
    </a>
  </li>
  {%- endfor -%}
</ul>

<meta http-equiv="refresh" content="0; URL='/books>
