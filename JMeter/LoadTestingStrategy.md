# Load Testing Strategy

## Understand the System
- Is it one monolithic service?
- Many microservices?
- Are there third-party dependencies maybe to an authentication service or a store or lots of other things that could potentially cause slowdowns.
- Are there data bases that you need to worry about and having the right numbner of connections to the database and caching the data?
- As far as caching solutions, are you using Redis, Kafka? Lots of options there that you need to know about.
- Are you hosting the service in-house or is it out in the cloud or maybe it's even serverless?

