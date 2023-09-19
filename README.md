# GraphQL
[Apollo Graph Developer](https://www.apollographql.com/tutorials/certifications/apollo-graph-associate/learning-path/)

## step 1 SCHEMA
A schema is like a contract between the server and the client. It defines what a GraphQL API can and can't do, and how clients can request or change data. It's an abstraction layer that provides flexibility to consumers while hiding backend implementation details.
```typescript
type SpaceCat {
    age: Int
    mission: [Mission]
}
```
description with comments

```graphql
"""
SpaceCat is a shema
"""
type SpaceCat {
   "this the name as String! non null"
  name: String!
  age: Int
  missions: [Mission]
}
```
## step 2 Backend
## step 3 Frontend

# -
- Which of these are benefits of schema-first design?
    - it reduces total development time.
    - it enables teams to work in parallel

<img width="989" alt="image" src="https://github.com/ju4nmoreno/GraphQL-notes/assets/11647634/5caf58d0-1fd5-43c6-bfa5-2720a8abf3b2">
- Which of these accurately describes a graph in GraphQL?
