---
testspace:
before:
  name: "github::beforeJob"
  description: "My before fixture description is here"
  input: "@before.json"
  _inactive_time: 3
after:
  name: "github::afterJob"
  description: "My after fixture description is here"
  input: "@after.json"
---

# Fixtures variables showdown

## Example scenario

Show how to access fixtures vars:

* Before fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.input }}
* After fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.input }}
