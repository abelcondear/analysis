## How would you build a backend for a SaaS website?

I would start by the followiing options:

- I can create an API that connects to database and then this API can provide the user the data extracted from database.
- I can create a microservice that connects to data layer and then this microservice outputs the data requiered by user.
- I can create a service that connects to database and then this service outputs the data or resource needed by user.
- I can create a custom connector that uses xml, yaml, or json to manipulate and connect to database and then this connector outputs the data required by user.