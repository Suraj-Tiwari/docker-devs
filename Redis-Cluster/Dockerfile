FROM redislabs/redismod:latest as builder

FROM bitnami/redis-cluster
COPY --from="builder" /usr/lib/redis/modules/* /opt/bitnami/redis/modules/
