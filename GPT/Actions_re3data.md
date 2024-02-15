## Authentification

None

## Schema

openapi: 3.0.0
info:
  title: re3data Repositories API
  version: beta
  description: This API provides access to repository data from re3data.org.

servers:
  - url: https://www.re3data.org/api/beta
    description: Production server

paths:
  /repositories:
    get:
      operationId: searchRepositories
      summary: Search repositories
      description: Retrieves a list of repositories based on a query string.
      parameters:
        - in: query
          name: query
          required: true
          description: Query string to search the repositories.
          schema:
            type: string
      responses:
        '200':
          description: Successful response
          content:
            application/json:
              schema:
                type: object
                properties:
                  totalHits:
                    type: integer
                    description: The total number of hits for the query.
                  data:
                    type: array
                    items:
                      $ref: '#/components/schemas/Repository'
        '400':
          description: Invalid request
        '500':
          description: Server error

components:
  schemas:
    Repository:
      type: object
      properties:
        id:
          type: string
          description: Unique identifier for the repository.
        name:
          type: string
          description: Name of the repository.
        url:
          type: string
          description: URL of the repository.
        description:
          type: string
          description: Description of the repository.

## Privacy Policy

https://www.re3data.org/legalnotice

