# nginx-tutorial


## Load Balancing
1. cd into server directory and run:
    - `docker build -t myserver`

2. Run 4 servers on containers with different ports
    - `docker run -p 1111:7777 -d myserver`


