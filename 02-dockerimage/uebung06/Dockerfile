FROM python:alpine3.20

LABEL Author="Linus Torvalds"

RUN apk add --no-cache python3 \
  && apk add --no-cache py3-pip

WORKDIR "/app"

CMD ["python3"]