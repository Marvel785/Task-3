# Task3

Pull the below images using docker pull:
- nginx
- node
- alpine
- php
- ubuntu
- spring pet clinic

Edit nginx container using : docker exec -it <CONTAINER ID> /bin/bash

Run nginx container using random port --> docker run -p 3442:80 -d nginx

To login --> docker login -u <username>

Save an image --> docker save -o <name.tar> <image name>

Load an image --> docker load -i <name.tar>
