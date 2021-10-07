# Nginx on Docker for give content
Docker-compose file and configuration file nginx to output content from a specified directory - "data"

# Why it's needed?

From time to time it is necessary to make files from some directory on your computer available via HTTP request. There are many ways to create tunnels to the user's local computer, such as "ngrok". This allows you to proxy traffic on a specific port.
However, when using the "Windows" operating system, there is a problem of "how to listen to the port". 
This repository presents a simple solution that allows you to make available the files placed in the "data" folder. 
From time to time it is necessary to make files from some directory on your computer available via HTTP request. There are many ways to get a domain for your computer, such as "ngrok"
