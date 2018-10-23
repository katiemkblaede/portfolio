---
layout: page
order: 2
---

# Wishlist

Unless otherwise noted, please assume I would like the exact item/brand I have listed. Items are listed from highest to lowest price. I have done my best to include shipping costs in the price listed.

{% assign wishlist = site.wishlist | sort: "price" %}
{% for item in wishlist %}
 {{ item.title }}
 {{ item }}
 ${{ item.price }}
{% endfor %}
