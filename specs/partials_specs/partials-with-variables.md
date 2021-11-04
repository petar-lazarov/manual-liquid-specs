---
testspace:
foo: bar
bar:
  baz: foo
---
# Partials with variables

## Example scenario

Check if partials with variables are working correctly: 

{% include context-variables-partial.md %}
{% include custom-defined-variables.md %}
{% include partial-with-local-variables.md myLocalVar="testing service" otherLocalVar=313 %}
