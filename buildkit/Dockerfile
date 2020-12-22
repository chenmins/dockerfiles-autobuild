FROM moby/buildkit:v0.6.1

USER root
COPY ca.crt /usr/local/share/ca-certificates/
RUN apk --no-cache add ca-certificates \
  && rm -rf /var/cache/apk/* \
  && update-ca-certificates


