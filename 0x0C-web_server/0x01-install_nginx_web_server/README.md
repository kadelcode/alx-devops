Readme:
- [-y on apt-get command](https://askubuntu.com/questions/672892/what-does-y-mean-in-apt-get-y-install-command)

Web servers are the piece of software generating and serving HTML pages, let's install one!

Requirements:
- Install ```nginx``` on your ```web-01```
- server
- Nginx should be listening on port 80
- When querying Nginx at its root ```/``` with a GET request (requesting a page) using ```curl```, it must return a page that contains the string ```Hello World!```
- As an answer file, write a Bash script that configures a new Ubuntu machine to respect above requirements (this script will be run on the server itself)
- You can’t use ```systemctl``` for restarting ```nginx```

Server terminal:

```
root@sy-web-01$ ./1-install_nginx_web_server > /dev/null 2>&1
root@sy-web-01$ 
root@sy-web-01$ curl localhost
Hello World!
root@sy-web-01$
```
