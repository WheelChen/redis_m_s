FROM redis

COPY redis-sentinel.conf /usr/local/etc/redis/redis-sentinel.conf

CMD [ "redis-sentinel", "/usr/local/etc/redis/redis-sentinel.conf" ]

EXPOSE 26379