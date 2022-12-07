FROM ubuntu:latest
COPY hello.sh /hello.sh
RUN apt update && apt install -y htop && apt clean

CMD ["sh", "/hello.sh"]
