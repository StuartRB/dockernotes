# dockernotes

Download docker for mac
```
docker pull rabbitmq:3-management
docker images
docker run -p 8080:15672 -p 5672:5672 -p 2022:22 <images_id>
open localhost:8080 for rabbitmq admin ui
docker exec -it <container_id>  /bin/bash
```
