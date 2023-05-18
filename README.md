# Docker build
```
git clone https://github.com/nowage/docker-test
cd docker-test/UbuntuDocker
docker build --rm -t nowage/ut:v2 .
docker images
```

# Docker run 
```
docker run -it --name ut -v ~/df:/df --rm nowage/ut:2
```
