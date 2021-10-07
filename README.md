# Nginx on Docker for give content
Docker-compose file and configuration file nginx to output content from a specified directory - "data"

# Why it's needed?

From time to time it is necessary to make files from some directory on your computer available via HTTP request. There are many ways to create tunnels to the user's local computer, such as "ngrok". This allows you to proxy traffic on a specific port.
However, when using the "Windows" operating system, there is a problem of "how to listen to the port". 
This repository presents a simple solution that allows you to make available the files placed in the "data" folder. 
From time to time it is necessary to make files from some directory on your computer available via HTTP request. There are many ways to get a domain for your computer, such as "ngrok"

# How it works
You need to install Docker on your computer. Once it is installed, simply navigate to the folder where you have cloned this repository and type the command: "docker-compose up -d"
The container with "nginx" will start up. Check if it works, go to your browser and type in the address "localhost". You will see a list of your files in the "data" folder.
Attention, the file with name "index.html" must not get into the folder, otherwise it will be executed 