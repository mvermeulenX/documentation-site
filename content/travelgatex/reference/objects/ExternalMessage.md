{
  "title": "ExternalMessage",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String",
      "name": "code",
      "url": "/travelgatex/reference/scalars/string",
      "description": "External Code",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String!",
      "name": "message",
      "url": "/travelgatex/reference/scalars/string",
      "description": "External Message",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": [
    {
      "name": "AdviseMessage",
      "description": "List of advise messages.",
      "url": "/travelgatex/reference/objects/advisemessage"
    }
  ],
  "enumValues": null,
  "operator": "type",
  "typename": "ExternalMessage",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}

## Required by

{{% graphql-require-by %}}