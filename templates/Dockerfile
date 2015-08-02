FROM gitinsky/baseimage:0.1.9
MAINTAINER Git in Sky <support@gitinsky.com>

RUN apt-get update && apt-get install -y memcached
ADD start.sh /start.sh
CMD ["/start.sh"]
