FROM ubuntu:20.04

WORKDIR /bin

COPY . /bin/

RUN ["chmod", "+x", "/bin/datainjector-1.0.1"]

EXPOSE 8000

CMD ["/bin/datainjector-1.0.1", "-c", "/bin/config.json"]
