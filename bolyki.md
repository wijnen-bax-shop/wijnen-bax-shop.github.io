---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
permalink: /bolyki/
---
![Bolyki](/images/features/Bolyki.jpg)
### Alle details van onze producten kan u terugvinden op onze website [hier](https://www.wijnen-bax.be).

{% for product in site.bolyki %}
  {% include product.html %}
{% endfor %}
