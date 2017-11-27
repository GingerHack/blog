---
layout: page
title: Links
---

# リンク集

## 各種サイトへのリンク

  - [conpass](https://gingerhack.connpass.com)
  - [GitHub](https://github.com/GingerHack)

## 参加メンバーのリンク

{% for loop in site.data.authors %}{% assign key = loop[0] %}{% assign author = site.data.authors[key] %}  - {{ author.name | escape }}{% if author.homepage %}
    - [Homepage]({{ author.homepage }}){% endif %}{% if author.github_username %}
    - [GitHub](https://github.com/{{ author.github_username }}){% endif %}{% if author.twitter_username %}
    - [Twitter](https://twitter.com/{{ author.twitter_username }}){% endif %}
{% endfor %}
