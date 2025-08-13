# GraphQL Queries – Character & Episode Data

This repository contains example GraphQL queries for fetching characters and episodes using the given endpoint.  

---

## 0. Query to Get a Specific Character by ID  
**Objective:** Retrieve a specific character’s information using their ID.  

**IDs Used:** `1`, `2`, `3`, `4`  

```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

query {
  character(id: 2) {
    id
    name
    status
    species
    type
    gender
  }
}

query {
  character(id: 3) {
    id
    name
    status
    species
    type
    gender
  }
}

query {
  character(id: 4) {
    id
    name
    status
    species
    type
    gender
  }
}
