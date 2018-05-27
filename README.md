# Insecure-Cross-Origin-Resource-Sharing-Check
CORS (Cross-Origin Resource Sharing) defines a mechanism to enable client-side cross-origin requests. This application is using CORS in an insecure way. The web application returns the following headers:  Access-Control-Allow-Credentials: true Access-Control-Allow-Origin: copy of the Origin header from request  In this configuration any website can issue requests made with user credentials and read the responses to these requests.

This simple HTML page allows you to check if the site is vulnerable to CORS or not.

Download the HTML file and enter the URL in the prompt window if any pop-up alerts then the site is vulnerable to CORS.
