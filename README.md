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
    - it's a collection of nodes and edges.
    - it's a representation of our app's data.

- Which of the following are valid field types?
    - String!
    - Int
    - [Int]
    - String

- What does an exclamation mark after a field's type indicate?
    - The field's value can't be null.

- Which of these are always true about the Query type?
    - it defines entry points into our schema.
    - it defines what data clients can query in oun schema.

- Which of these are purposes of a GraphQL server?
    - Validating GraphQL queries against our schema
    - Receiving incoming GraphQL queries
    - Returning populated schema fields as a respones

- Which of these are true about querying Apollo Server without a connected data source?
    - You can enable default mocked responses for every schema field.
    - you can fonfigure custom mocked responses for every schema field.

- Which of these are benefits of using the Apollo Studio Explorer?
    - You can build and iterate on queries faster.
    - You can step through your schema to descover available types and fields.
