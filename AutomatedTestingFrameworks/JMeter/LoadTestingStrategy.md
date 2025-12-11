# Load Testing Strategy

## Understand the System
- Is it one monolithic service?
- Many microservices?
- Are there third-party dependencies maybe to an authentication service or a store or lots of other things that could potentially cause slowdowns.
- Are there data bases that you need to worry about and having the right numbner of connections to the database and caching the data?
- As far as caching solutions, are you using Redis, Kafka? Lots of options there that you need to know about.
- Are you hosting the service in-house or is it out in the cloud or maybe it's even serverless?

## What to look for
- Slow APIs (> 250)
- Duplicated Calls
- Call Frequency
- Calls in correct order
- What are the APIs that are used the most?
- What are the APIs that take up the most energy or memory or time in your system and what APIs are the most critical?
- Which are the ones that you really can't afford to have go down?

## Kinds of Load Tests
- Session Based - Replicates the actions of an actual user.
- Stress - Pushes the limits of a service.
- Soak - Running the tests for a long time. 
- Benchmark - Quick tests run in a CI pipeline.

## Serverless Testing
- Throttling: Account vs Function
- Cold Start Issues
- More memory == more $$$
- More compute time == more $$$

## Factors for considering Load Testing
- For both client and server, test performance early and often.
- Make sure the client can adapt to varying network and server conditions.
- Find the performance limits of your servies.
- Be confident that your application is ready for the masses.