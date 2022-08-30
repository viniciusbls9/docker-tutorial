# docker tutorial

# Commands in WSL 

Connect docker daemon

```
sudo service docker start
```

Run docker image (get local or install from internet)

```
docker run image-name
```

Run docker image (get local or install from internet) without crash your terminal

```
docker run -d image-name
```

See installed image

```
docker image ls
```

Remove local image

```
docker rmi image-name
```

Force remove local image

```
docker rmi image-name -f
```

Stop container

```
docker stop container-id
```

Reference: https://www.youtube.com/watch?v=F_pgDkErFIk
