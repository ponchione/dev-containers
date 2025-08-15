FROM golang:latest-alpine 

WORKDIR /app

RUN apk add --no-cache git gcc libc-dev build-essential sqlite-tools

CMD ["go", "run", "."]