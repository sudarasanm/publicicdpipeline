FROM ubuntu:20.04

WORKDIR /bin

COPY . /bin/

RUN ["chmod", "+x", "/bin/pl_gprm_v0.2"]

EXPOSE 4005

CMD [ "/bin/pl_gprm_v0.2", "-c", "/bin/config.json" ]
