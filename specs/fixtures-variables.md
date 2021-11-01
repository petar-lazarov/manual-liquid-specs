---
testspace:
before:
  name: "github::beforeJob"
  description: "My before fixture description is here"
  input:
    a: before this
    b: before that
after:
  name: "github::afterJob"
  description: "My after fixture description is here"
  input:
    a: after this
    b: after that
---

# Fixtures variables showdown

## Example scenario

Show how to access fixtures vars:

* Before fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.input }}
* After fixture: {{ spec.before.name }} - {{ spec.before.description }} - {{ spec.before.input }}
