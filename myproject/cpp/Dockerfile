FROM ubuntu:latest


WORKDIR /app


RUN apt-get update && apt-get install -y \
    g++ 


COPY Random.h .


COPY project.cpp .


RUN g++ -o project project.cpp 


EXPOSE 8080


CMD ["./project"]
