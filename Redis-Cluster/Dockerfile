FROM redislabs/redismod:latest as builder

FROM bitnami/redis-cluster:7.0.4-debian-11-r14
COPY --from="builder" /usr/lib/redis/modules/* /opt/bitnami/redis/modules/
CMD "/opt/bitnami/scripts/redis-cluster/run.sh"
