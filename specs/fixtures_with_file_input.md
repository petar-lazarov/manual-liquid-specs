---
testspace:
before:
  name: "github::beforeJob"
  description: "My before fixture description is here"
  payload: "@before.json"
after:
  name: "github::afterJob"
  description: "My after fixture description is here"
  payload: "@after.json"
---

# Fixtures variables showdown

## Example scenario

Show how to access fixtures vars:

* Before fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.payload }}
* After fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.payload }}
