FROM alpine
RUN apk add curl wget busybox-extras netcat-openbsd python3 py-pip && pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
