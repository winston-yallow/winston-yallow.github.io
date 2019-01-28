---
layout: basic
---

# Home

Github Repositories:

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

This is the landing page for my blog.

![User Icon]({{ site.github.owner_gravatar_url }})

Here are some code snippets:
```
# This is a small test
foo = "bar"
if foo == "bar":
    print('foo equals "bar"')
```

Inline: `foo == "bar"`

- a list item
- another item

1. Ordered Item A
2. Ordered Item B
3. Ordered Item C

> This is a quote!

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Horizontal Line

---

Some raw HTML

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
