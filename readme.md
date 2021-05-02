# Introduction
There are total 8 issues, each student is required to finish one. We have *create an issue* and *project board*. After creating the readme.md, we will _show our team B to the internet_ to let more people know us. Then, we will _keep checking_ and _write C code_. After that, we will _get a status badge_. And finally, _promoting our repo_.
# Code

```C

{% include_relative code.c %}

```

# Contributors
{% for stu in site.stu %}
  <div style="text-indent: 5%;">
    »<img src="{{ stu.image }}" width="50" height="50" style="display:inline;"><a href="https://github.com/{{ stu.user }}" style="text-decoration:none;color:inherit;"> @{{ stu.user }}</a> ({{ stu.name }})
    <p style="text-indent: 10%;">»{{ stu.content }}</p>
  </div>
{% endfor %}
