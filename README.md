There are various types of query parameters that serve different purposes. Here are some common types with examples:

1. **Filtering Parameters**: These parameters allow you to filter data based on specific criteria. For example, to retrieve a list of active users, you can use the "status" query parameter: `GET /users?status=active`.

2. **Sorting Parameters**: Sorting parameters enable you to specify the order in which the data should be returned. For example, to retrieve a list of products sorted by price in ascending order, you can use the "sort" query parameter: `GET /products?sort=price:asc`.

3. **Pagination Parameters**: Pagination parameters are used to control the amount of data returned in a single API response and navigate through large datasets. For example, to retrieve the second page of a list of products with 10 items per page, you can use the "page" and "limit" query parameters: `GET /products?page=2&limit=10`.

4. **Searching Parameters**: Searching parameters allow you to perform text-based searches on the data. For example, to search for products containing the keyword "shoes", you can use the "search" query parameter: `GET /products?search=shoes`.

5. **Embedding Parameters**: Embedding parameters enable you to include related resources in the API response. For example, to retrieve a user and embed their associated posts, you can use the "embed" query parameter: `GET /users/1?embed=posts`.

6. **Custom Parameters**: API providers can define custom query parameters to support specific functionality or requirements. These parameters are specific to the API and may vary from one API to another. For example, an API for weather data might have a custom "units" query parameter to specify the unit of measurement: `GET /weather?location=NewYork&units=celsius`.
