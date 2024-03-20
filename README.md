# Web-Proxy-Server
 Computer Networks Mini Project on Web Proxy Server

# Description
This is a Python web proxy server implemented using sockets. It allows you to create a simple proxy server that can handle HTTP requests and responses.

# Features
Accepts incoming connections and acts as a proxy between clients and servers.
Supports basic HTTP GET requests.
Easily configurable proxy host and port.

# Prerequisites
Python 3.x
Internet connection (if you want to proxy external websites)

# Usage
Clone this repository to your local machine
Navigate to the directory: cd python-proxy-server
Modify the proxy_host and proxy_port variables in the main() function of proxy_server.py according to your requirements.
Run the proxy server:
The server will prompt you to enter a listening port. Enter a port number and click OK.
Once the server is started, you can send HTTP requests to it.

# Configuration
To change the listening port of the proxy server, modify the listen_port variable in the main() function of proxy_server.py.
To change the maximum number of connections allowed, modify the max_conn variable in proxy_server.py.
To change the buffer size for sending and receiving data, modify the buffer_size variable in proxy_server.py.

# Contributing
Contributions are welcome! Feel free to submit pull requests or open issues if you find any bugs or want to suggest improvements.
