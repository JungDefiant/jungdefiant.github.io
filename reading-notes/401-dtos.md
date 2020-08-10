### Data Transfer Objects

When sending data over a network, it's better to decouple the database information from the data sent 'over the wire'. In this case, a *data transfer object* is used. DTO's have other uses as well. A particular action might only need specific information from a data object, so only those specific pieces of information will be included in the DTO. Ideally, DTO's are read-only and serialized to ensure the data sent is usable across different types of systems built on different programming languages.

In the context of ASP.NET, DTO's are classes separate from entity classes used to represent data. When a request is sent through a route, the controller will return a DTO instead of the entity.
