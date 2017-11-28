# Starter Repo for React-Apollo-GraphCool

* [Apollo Client](https://github.com/apollographql/apollo-client): Fully-featured, production ready caching GraphQL client
* [Graphcool](https://www.graph.cool): Backend development framework based on GraphQL + Serverless

### How to use

replace uri with Graphcool SIMPLE API endpoint

src/index.js
```
const httpLink = new HttpLink({
  uri: "__SIMPLE_API_ENDPOINT"
});
```
