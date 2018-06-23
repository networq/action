networq:action
====

This is the "networq:action" package for [NetworQ](https://github.com/networq).

## Types

This package defines the following types that you can use in your own Networq:

### networq:action:action type

Fields:

  * `status`: *string*
  * `details`: *string*
  * `trigger`: *string*
  * `assignee`: *networq:action:assignee*
  * `list`: *networq:action:list*
  * `completedAt`: *string*

### networq:action:assignee type

Fields:

  * `actions`: *networq:planning:action*

### networq:action:list type

Fields:

  * `actions`: *networq:action:action[]*

