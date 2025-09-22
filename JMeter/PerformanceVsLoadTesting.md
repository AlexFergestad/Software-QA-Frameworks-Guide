# Performance Vs. Load Testing
- Performance - The Speed of an action or set of actions on a single client or server instance.
- Load - The number of requests a service can handle in a given period of time. 

## Client Performance
- Network Conditions - The way your website or application handles various network conditions is going to have the greatest impact on how people experience your application.
- Number of Resources - The Number of Resources needed to load your webpage or to run your application is also a major factor, not just the quantity of resources but also the size.
- Image Rendering - The most visible aspect of client performance and is definitely something that needs to considered. If you have a lot of images or complex set of images, it's going to take lonnger than something that's simple.
- Server Performance - If your application is making an API call and that API call takes a long time, that of course it's going to affect the perceived speed of your application.

## Server Performance
- Host Configuration - How many boxes is the service running on? How much CPU do they have? How much memory do they have? Are they in the cloud? Are they co-located with the database? There's a lot of different aspects here to do with the configuration of the service and they can all have a major impact on the server performance.
- Data Access - Almost all services are working with data in some respect. If that data is in a database, does the service need to retrieve it every time or is it cached for faster access?
- Third-Party-Services - If your service is working with a lot of other physical devices or in a microservice environment, that can also have a big effect on the performance of your server.
- Compute Requirements - If you're doing a lot of complex algorithms or data management, that's going to take longer than just retrieving information and giving it back to the client.
- Client Load - Your server might work great with one client attached to it, but when it has a million clients attached to it, it's going to be a lot more difficult for it to work in a speedy fashion.

## Performance & Load Testing Go Together
- A well-performing client can reduce overall load on a service.
- The better a service performs, the more load it will be able to handle.
- Should be started as early in the release cycle as possible.

## Quick Takeaways
- *If a site is slow, people are more likely to leave.
- *Load Tests focus on how many requests a service can handle in a given period of time.
- *The factors that impact client performance are server performance and the number and complexity of scripts.
- *The factors that impact server performance are host configuration, the number of client requests, and data caching. (Data caching - The process of temporarily storing copies of data in a high-speed local storage location (the cache) to serve future requests for that data much faster than accessing the original, slower source)
- *Poor server performance affects the total number of clients it can handle.