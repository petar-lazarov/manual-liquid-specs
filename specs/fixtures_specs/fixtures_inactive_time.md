---
testspace:
before:
  name: "github::beforeJob"
  description: "My before fixture description is here"
  _inactive_timeout: 2
after:
  name: "github::afterJob"
  description: "My after fixture description is here"
---

# Fixtures variables showdown

## Example scenario

Show how to access fixtures vars:

* Before fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.input }}
* After fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.input }}
