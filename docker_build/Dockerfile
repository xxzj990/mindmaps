FROM centos:7.2.1511

ENV PATH /opt/node-v6.9.4-linux-x64/bin:$PATH

ADD https://nodejs.org/dist/v6.9.4/node-v6.9.4-linux-x64.tar.xz /opt

RUN cd /opt

RUN ls /opt

RUN tar -xvf node-v6.9.4-linux-x64.tar.xz

RUN rm -f node-v6.9.4-linux-x64.tar.xz

ENTRYPOINT ["/usr/sbin/nginx"]
