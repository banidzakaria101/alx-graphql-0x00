# GraphQL Episode Query

This project contains a sample GraphQL query to fetch episode data using the `episode(id: ID!)` field.

## Objective

Write and execute a GraphQL query to retrieve details of a specific episode using its ID.

## Endpoint

Use the provided GraphQL endpoint (e.g., Rick and Morty GraphQL API: `https://rickandmortyapi.com/graphql`) or another endpoint if specified.

## Requirements

- Create a `.graphql` file containing the query  
- Create a `.json` file containing the output of the query

## Fields to Include in Query

- `id`  
- `name`  
- `air_date`  
- `episode`

## File Structure

bash
episode/
├── README.md
├── episode-page-1.graphql
├── episode-page-1-output.json
Sample GraphQL Query
graphql
Copier
Modifier
query GetEpisodeById {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}

## How to Run
Use a GraphQL client like Apollo Studio, Insomnia, or Postman to run the query against the API endpoint.
Copy the response into episode-page-1-output.json.

## Completion
Once the query and response are complete, push your files to the alx-graphql-0x00 repository and request manual review before the deadline.

## License
This project is part of the ALX Software Engineering Program. All rights reserved.