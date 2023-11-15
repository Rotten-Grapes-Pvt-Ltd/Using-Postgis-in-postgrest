# Using PostgREST functionality 

PostgREST has tons of built in features which makes it suitable for using it as production level API provider

1. Authentication - 

Allow  anonymous as well as secured users to access the data using token and custom login functions as well. Checkout more info [here](https://postgrest.org/en/stable/references/auth.html)

2. Querying - 

PostgREST supports various *Operators* which can help querying various data formats such as String, Numerics, Boolean, DateTime, List, etc. 

Checkout operators [here](https://postgrest.org/en/stable/references/api/tables_views.html#operators)

3. Computed fields - 

Users can create virtual columns on the fly, which can help create custom data without storing data in table. 
Checkout how to create custom fields [here](https://postgrest.org/en/stable/references/api/computed_fields.html)

4. Relationships - 

PostgREST can understand *many-to-many* and *one-to-one*, and can return the data in nested dictionary format.

Checkout more info [here](https://postgrest.org/en/stable/references/api/resource_embedding.html)

5. Response Format - 

Data can be exported in 

- text/csv
- application/json
- application/openapi+json
- application/geo+json

For a single response, user can request data as a JSON rather than List by using `Accept: application/vnd.pgrst.object+json` format.