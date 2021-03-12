---
testspace:
---

# Context Variables showdown

In this spec we are listing all default context variables using liquid spec

## Example Scenario

Context Variables:


* user: {{ user.id }}, {{ user.name }}
* project: {{ project.id }}, {{ project.name }}, {{ project.url }}
* space: {{ space.id }}, {{ space.name }}, {{ space.url }}
* cycle: {{ cycle.id }}, {{ cycle.name }}, {{ cycle.url }}, {{ cycle.issue_id }}
* session: {{ session.id }}, {{ session.name }}, {{ session.url }}
* spec: {{ spec.id }}, {{ spec.name }}, {{ spec.filename }}
* repo: {{ repo.url }}, {{ repo.branch }}
