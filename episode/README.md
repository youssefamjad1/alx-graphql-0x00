# Episode Queries

This directory contains GraphQL queries and their corresponding output files to fetch details of specific episodes by ID from the Rick and Morty API.

## Files

- `episode-id-1.graphql` to `episode-id-4.graphql`: GraphQL queries to fetch episodes with IDs 1 to 4.  
- `episode-id-1-output.json` to `episode-id-4-output.json`: JSON responses returned by the API for the respective queries.  
- `README.md`: This file.

## Query Structure

Each query uses the `episode(id: ID!)` field and requests the following fields for an episode:

- `id`  
- `name`  
- `air_date`  
- `episode`

## Usage

1. Open the GraphQL playground at https://rickandmortyapi.com/graphql  
2. Paste the queries from the `.graphql` files and run them.  
3. Save the JSON response into the matching `-output.json` files.

---
