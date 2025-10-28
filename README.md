# Data Analysis

## Education
MSc Psychology: Research Methods and Statistics

BSc Applied Psychology

## Work Experience

## Projects
{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})
{{ project.content | strip_html | truncate: 200 }}
{% endfor %}

