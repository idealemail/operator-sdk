FROM registry.access.redhat.com/ubi8/ubi-minimal:latest

COPY operator-sdk-dev-linux-gnu  /usr/local/bin/operator-sdk

RUN microdnf install -y golang make which

ENTRYPOINT ["/usr/local/bin/operator-sdk"]
