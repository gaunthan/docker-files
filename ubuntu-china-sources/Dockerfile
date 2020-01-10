FROM ubuntu:18.04
COPY sources.list.china /etc/apt/
RUN cp /etc/apt/sources.list /etc/apt/sources.list.orig \
	&& cat /etc/apt/sources.list.china >> sources.list \
	&& apt update
