---
layout: layout.html
---
<html>
  <head>
    <title>
      home
    </title>
  </head>
  <body>
<ul>
{%- for book in collections.book reversed -%}
  <li>
    <a href="{{book.url}}">
      {{ book.data.title }}
    </a>
  </li>
  {%- endfor -%}
</ul>
  </body>
  </html>
