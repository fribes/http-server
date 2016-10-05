# Building docker image

```
docker build -t http-server .
```

# Running container

```
docker run -p 442:8080 -d http-server
```

# Tips

## Add current user to docker group

```
sudo usermod -aG docker $(whoami)
```

