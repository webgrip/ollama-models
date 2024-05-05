# bash into the docker container by awking the container id from `docker ps` and then running `docker exec -it <container_id> /bin/bash`
`docker exec -it $(docker ps | awk '/ollama/ {print $1}') /bin/bash`
`apt-get install nano`
`nano Modelfile`
`ollama create example -f Modelfile`
