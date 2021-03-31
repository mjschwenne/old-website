---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

This is a test of the system. I hope that this works.

~~~html
{% for post in site.posts %}

	(post.title)[post.url]

{% endfor %}
~~~
