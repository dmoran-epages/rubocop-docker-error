# CLean build docker images and container, then run
> docker stop $(docker ps -a -q);  docker rm -v $(docker ps -a -q); docker rmi $(docker images -q); docker build -t mydocker -f dockerfile .; docker run --name  mydocker  -v $PWD/rails:/app-code -it mydocker /bin/bash 


# in the terminal when ready, type:

> rubocop
invalid byte sequence in US-ASCII
..........
