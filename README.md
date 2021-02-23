
### Links

- [Profile](https://github.com/yutkat)
- [GitBook](https://yutkat.gitbook.io/katapedia/)

### Blog

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>

### Activity

<a class="twitter-timeline" data-theme="dark" href="https://twitter.com/yutkat?ref_src=twsrc%5Etfw">Tweets by yutkat</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
