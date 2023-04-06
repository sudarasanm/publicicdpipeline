FROM ubuntu:20.04

WORKDIR /bin

COPY . /bin/

RUN ["chmod", "+x", "/bin/pql"]

EXPOSE 8005

CMD ["/bin/pql"]