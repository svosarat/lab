FROM alpine
RUN apk add curl wget busybox-extras netcat-openbsd python py-pip bash
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
