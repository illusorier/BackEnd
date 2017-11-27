GraphQL is a query language for your API.

Practically speaking, the GraphQL layer lives between the client and one or more data sources, 

A GraphQL API is organized around three main building blocks: the **scheme**, **queries**, and **resolvers**.

### Queries

        query {
          stuff
        }
        
We're declaring 

Your GraphQL server won't know what to do with an incoming query unless you tell it using a **resolver**.

