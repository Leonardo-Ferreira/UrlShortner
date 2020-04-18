# UrlShortner
Sample project on various subjects: Azure Pipelines, Cosmos DB, Architectural Patterns, and others

## Main Business Objective
Provide a service where a any user can insert any url and get a short version of it.

### Details
1. Any url is accepted.
2. If a url that is already present is provided, it is accpetable that a new short url is provided
3. The shortned url should in the format https://{domain}/{identifier}
4. The identifier is not fixed length
5. The identifier should be as short as possible while guaranteeing that no clash will happen
6. The identifier is case sensitive
