URL Shortener Microservice
==========================

https://url-shortener-fcc.herokuapp.com/

Pass a URL as a parameter to receive a JSON string containing a shortened URL that will redirect to the original site.

-   Validates URI before querying and saving to the database.
-   Will not create duplicate short urls for the same URL.
-   Creates a new short URL for each original URL.
-   Redirects to original URL from the input short URL.