FROM muzyka/php5-fpm:0.0.1

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y nginx-extras && \
    apt-get autoremove ; \
	apt-get clean
