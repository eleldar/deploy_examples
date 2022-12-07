docker build -t eleldar/hello:v2 .
docker login -u eleldar
# Username
# Password
docker push eleldar/hello:v2
##################################
docker pull eleldar/hello:v2
docker run -it --rm hello:v2 bash
