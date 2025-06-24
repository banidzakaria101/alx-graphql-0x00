# GraphQL Character Query

This project contains sample GraphQL queries to fetch character data using the `character(id: ID!)` field.

## Objective

Write and execute GraphQL queries to retrieve specific character information using their IDs.

## Endpoint

Use the provided GraphQL endpoint (e.g., Rick and Morty GraphQL API: `https://rickandmortyapi.com/graphql`) or another endpoint if specified.

## Requirements

For each character ID (1, 2, 3, 4), create:

- A `.graphql` file containing the query
- A `.json` file containing the output of the query

## Fields to Include in Query

- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## File Structure

character/
├── README.md
├── character-id-1.graphql
├── character-id-1-output.json
├── character-id-2.graphql
├── character-id-2-output.json
├── character-id-3.graphql
├── character-id-3-output.json
├── character-id-4.graphql
├── character-id-4-output.json

bash
Copier
Modifier

## Sample GraphQL Query

  graphql
query GetCharacter1 {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
## How to Run
Use a GraphQL client like Apollo Studio, Insomnia, or Postman to run the queries against the API endpoint.

Copy the response into the corresponding *-output.json file.

## Completion
Once all queries and responses are complete, push your files to the alx-graphql-0x00 repository and request manual review before the deadline.

## License
This project is part of the ALX Software Engineering Program. All rights reserved.