## Alumni

### PhD

{% for s in site.data.students.alumni.phd %}

- {{ s.name }}, PhD, {{ s.year }}
  {% endfor %}

### Master

{% for s in site.data.students.alumni.ms %}

- {{ s.name }}, MS, {{ s.year }}
  {% endfor %}
