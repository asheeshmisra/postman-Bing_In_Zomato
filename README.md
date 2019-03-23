# Bing In Zomato
This is a public repository having a postman collection to search for a restaurant near a specified place using Zomato API and Bing Maps REST API.

This collection uses environment variables across different requests. To make any request to Zomato API, its key, stored as environment variable is passed in request's header. Similarly, Bing Maps REST API key is also passed in its request. When the collection is exported from Postman, the environment variables are NOT exported by default. Therefore, to use this collection, please obtain keys from Zomato API and Bing Maps REST API from their respective sites and save them as environment variables. Procedure of doing so is given in the tutorial as the following url:

