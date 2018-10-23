---
layout: page
order: 3
---

# Wishlist

Unless otherwise noted, please assume I would like the exact item/brand I have listed. Items are listed from highest to lowest price. I have done my best to include shipping costs in the price listed.

{% assign wishlist = site.wishlist | sort: "price" | reverse %}
{% for item in wishlist %}
  <h3>
    {% if item.link %}<a href="{{ item.link }}" target="_blank">{% endif %}
      {{ item.title }}
    {% if item.link %}</a>{% endif %}
    <span>{{ item.price }}</span>
  </h3>
  {{ item }}
{% endfor %}

## Gift Cards

Alibris, Gap/Old Navy, Google Play, IKEA, Michaels, Sweetapolita, Target, Tattered Cover, World Market

## Surprise me with things I’d like!

animation, baking and cooking, crafting and sewing, Disney/Disneyland, drawing and illustration, graphic design, small space/indoor gardening, yoga

<style>
  .page div.whole {
    float: none;
    margin-left: auto;
    margin-right: auto;
    max-width: 640px;
    width: 80%;
  }

  h2 {
    margin-top: 1.5em;
  }

  h3 {
    margin: 1.5em auto 0;
  }

  h3 span {
    font-weight: 300;
  }

  h3 + p {
    font-style: italic;
    margin-top: 0;
  }
</style>

