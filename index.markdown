---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
>> Welkom op de webshop van Hungarian Wines Bax.  
Alle details van onze wijnen kan u terugvinden op onze website [hier](https://www.wijnen-bax.be).

{% for product in site.products %}
  {% include product.html %}
{% endfor %}
