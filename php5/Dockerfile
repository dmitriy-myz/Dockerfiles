FROM debian:stable
ENV HOME=/root

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y php5-fpm php5-pgsql php5-curl php5 php5-cli && \
    apt-get autoremove ; \
	apt-get clean
