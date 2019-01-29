---
layout: basic
---

<div class="card text-white bg-danger mb-5">
  <div class="card-body">
    <h4 class="card-title">Warning!</h4>
    <p class="card-text">
      This blog is currently under construction.<br>
      You won't find any content here.<br>
      You may find problems.
    </p>
    <p class="card-text">
      If you find a bug feel free to open a GitHub issue.
    </p>
    <a href="{{ site.github.issues_url }}" class="btn btn-secondary octicon-white">{% octicon bug %}&nbsp;&nbsp;GitHub Issues</a>
  </div>
</div>

{% for post in site.posts %}
  {% include post_preview.html postdata=post last=forloop.last %}
{% endfor %}
