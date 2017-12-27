URL Shortener Microservice
=========================

**Objective:** Build a full stack JavaScript app that is functionally similar to this: [https://url-shortener-microservice-es.glitch.me](https://url-shortener-microservice-es.glitch.me) and deploy it to Glitch.

User Stories
------------
- I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
- If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.
- When I visit that shortened URL, it will redirect me to my original link.

Example creation usage:
-----------------------
`https://url-shortener-microservice-es.glitch.me/new/https://www.google.com`  
`https://url-shortener-microservice-es.glitch.me/new/http://foo.com:80`

Example creation output:
------------------------
`{ "original_url":"http://foo.com:80", "short_url":"https://url-shortener-microservice-es.glitch.me/8170" }`

Usage:
------
`https://url-shortener-microservice-es.glitch.me/2871`

Will redirect to:
-----------------
`https://www.google.com/`