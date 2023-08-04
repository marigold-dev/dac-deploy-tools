ARG BASE_IMAGE
FROM ${BASE_IMAGE}
# eg, tezos/tezos-bare:master_a78b70c7_20230724101956

USER root

RUN apk update && \
    apk add bash curl

USER tezos