FROM redis:latest
RUN mkdir -p /etc/redis
COPY redis.conf /etc/redis/redis.conf
VOLUME /data
CMD ["redis-server"]
expose 6379
