FROM alpine:latest

RUN apk update && \
    apk add bash python3 py3-pip git i2c-tools && \
    pip3 install smbus

CMD [ "/bin/bash" ]