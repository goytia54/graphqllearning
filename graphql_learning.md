# GraphQL learning

## Data types
* Strings
* Int
* Boolean
* Float
* Custome types: `type MockType {}` which can be embedded in another type
* Enum types: a type of validation
* Arrays: `[datatype]`

## Aliases
* Two or more queries in one query request

## Fragment
have to use the same type of data with an alias

`...friendFragment`

```
fragment friendFragment on Friend {
  firstName
  lastName
}
```
