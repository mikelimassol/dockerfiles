## Dockerfile for sensu-server

### How to Use

 1. git clone && cd repo
 1. docker build -t your-image .
 1. docker run -t -i -p 8080 your-image /bin/bash
 1. run /root/start.sh
 1. Please access to http://your-image:8080/