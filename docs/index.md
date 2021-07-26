## 优麒麟Ubuntu Kylin入门教程

本教程面向没有电脑使用经验或者经验较少的读者，没有高深的使用技巧，重点分享优麒麟的日常使用，希望能为读者带来一定的帮助。

### 文章列表

<ul>
  {% for post in site.posts %}
    <li>
      <a target="_blank" href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for post in site.posts %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }} target=“_blank”){:target=“_blank”}
{% endfor %}