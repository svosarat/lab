FROM alpine
RUN apk add openssh
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
