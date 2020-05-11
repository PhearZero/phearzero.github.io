---
short_name: owner
role: Project Owner
image: imgs/Skull-649.png
---
This is ``{{ site.github.owner_name }}``'s author page. It represents the ``Project Owner`` role in the current repo.

 - User Page? {{ site.github.is_user_page }}
 - Issues? [link]({{ site.github.issues_url }})


{% if site.github.is_project_page %}
## Project ``{{ site.github.project_title }}`` in ``{{ site.github.environment }}``
 - Github Wiki? {{ site.github.wiki_url | default: false }}
{% endif %}




```json
{{ site.github }}
```