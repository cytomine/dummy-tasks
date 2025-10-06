FROM alpine:3.19.1

COPY scripts/identity.sh /identity.sh
RUN chmod +x /identity.sh

ENTRYPOINT ["/identity.sh"]
