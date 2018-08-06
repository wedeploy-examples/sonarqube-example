FROM postgres:10.4-alpine

COPY --from=healthcheck/postgres /usr/local/bin/docker-healthcheck /usr/local/bin/

HEALTHCHECK CMD [ "docker-healthcheck" ]