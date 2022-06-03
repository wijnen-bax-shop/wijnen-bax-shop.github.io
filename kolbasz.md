---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
permalink: /kolbasz/
---
# Kolbasz
### Alle details van onze producten kan u terugvinden op onze website [hier](https://www.wijnen-bax.be).

{% for product in site.kolbasz %}
  {% include product.html %}
{% endfor %}
