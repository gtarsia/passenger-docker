FROM phusion/baseimage:0.10.1
MAINTAINER Phusion <info@phusion.nl>

ADD . /pd_build
RUN /pd_build/install.sh
CMD ["/sbin/my_init"]
EXPOSE 80 443
