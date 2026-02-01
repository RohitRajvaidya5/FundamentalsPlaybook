# Middleware

## Defination

Middleware is a layer in django that possesses requests before they reach the view and responses before they send back to client.


## Infographics

<p align="left">
  <img src="/assets/Middleware.png" width="800" style="border-radius: 12px;" />
</p>


### Explanation

Simple workflow is look like this :

**user (browser) &rarr; WSGI / ASGI &rarr; Middleware &rarr; URL Conf &rarr; Django View &rarr; Middleware &rarr; Response**

