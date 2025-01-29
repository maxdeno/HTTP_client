# HTTP_client
This is a simple http_client wriiten in python. It sends GET requests to an http_server and retrieves a specific file requested by the user.
It sends the GET request over a TCP connection

## 📌Features
- Sends **HTTP GET requests** to any server
- Uses **sockets** for direct communication
- Displays **server responses**
- Supports **custom host, port, and file path**

# 🚀usage
1. Run a local server:<br>
     `python web_server.py 6789` <br>
        or<br>
   The python server:<br>
     `python -m http.server <port_no>`

2. Connect the http_client to the server:<br>
     `python http_client.py example.com 80 /index.html`


# 🎈Implementation
HTTP_Server:
HTTP_client:
