# CORS_POC
It is designed to demonstrate potential CORS misconfigurations in web applications, where sensitive data or API responses may be accessible across different origins without proper validation.

Go to your project folder:

cd cors-poc

(Make sure index.html and result.html are inside this folder.)

Start Python HTTP server

python3 -m http.server 8080

This will start a local server on port 8080.

Access in browser

http://<server-ip>:8080/index.html

Replace <server-ip> with:

localhost if running on same machine

Your Linux server’s public IP if accessing remotely

Use the PoC

Enter Endpoint, HTTP Method, and Bearer Token in index.html.

Submit request → Result will be shown on result.html.


