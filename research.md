# Research

<ul>
{% for post in site.posts %}
    <li>
        URI: <a href="{{post.url}}">{{post.url}}</a> {{post.title}}
    </li>
{% endfor %}
</ul>