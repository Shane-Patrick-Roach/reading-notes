
# Systems Design: Scalability


## Topics covered:

- Vertical scaling
- Horizontal scaling
- Caching
- Load balancing
- Database replication
- Database partitioning

---

## Vertical Scaling

- Vertical scaling keeps your existing infrastructure but adds computing power.
- Existing pool of code does not change. Simply run on machine with better specs.
- Adding more resources to a single node and adding additional CPU, RAM, and Disk to cope with an increasing workload.
- Draaawbacks of higher risk for downtime and outages.

## Horizontal Scaling

- Adds more instances of machines without first implementing improvemnts to existing specifications.
- By scaling out you share the processing power and load balancing across multiple machines.


## Load Balancing 

- Distribute incoming client requests to computing resources such as application servers and databases.
- Returns response from the computing resource to the appropriate client.
- They are effectice at => preventing requests from going to unhealthy servers, preventing overlaoding resources, helping elimate single points of failure.
- They can help with horizontal scaling, improving performances na d availbility.
- Introduces complexity and involves cloning servers. => servers should be stateless, not contain any user-related data like sessions or profile pictures.
- Can become a bottle neck if it does not have enough resource or if it is not configure properly. A single load balancer is a single point of failure, configuring multiple load balancers further increase complexity.

Load Balancers can route traffic based on various metrics, including;

- Random
- Least Loded
- Session/cookies
- Round Robin or weighted round robin

### Key Concepts

- Load balancer has its own IP address
- How can it decide what server to send it to?
- The load balancer decides which backend server to send you to. Risks overloading a specific server.


## Caching

- Caching improves paage load times and can reduce the load on your servers and databases. 1) lookup cache 2) if found, return to the client 3) Otherwise, forward to worker, sotre to cache.
- putting a chace in front of a database caan help absorb uneven loads and spikes in traffic. 
- Disadvantages => need to maaintain consistency between caches and the source of truth such as the daatabse through cache invalidation.
- Cache invalidation is a difficult problem. 


## Federation

- Splits up databases by function. For example, insteada of a single, monolithic daatabase, you could have three databases, forums, users, and products. 
- Smaller databases result in more data that can fit in memory, which in return results in more cache hits due to imnproved cache locality.
- Disadvantages include; not effective if schema requires huge functions or tables. Adds more hardwaare and additional complexity.
- Joining data from two databases is more complex with a server link.





## Resources

- [Intro to Scalability](https://www.youtube.com/watch?v=-W9F__D3oY4&ab_channel=JorgeScott)
