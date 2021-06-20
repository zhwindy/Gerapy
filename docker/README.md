# Docker

## Build

change to root folder, and exec:

```
docker build -t gerapy -f docker/Dockerfile .
```

### build
```
docker build -f ./docker/Dockerfile -t gerapy:mysql .
```

### add tag
```
docker tag gerapy:mysql zhwindy/gerapy:mysql
```

### push
```
docker push zhwindy/gerapy:mysql
```