FROM golang:1.25.0-alpine 

WORKDIR /api

COPY ./go.mod /api/

RUN apk add --no-cache git gcc libc-dev build-essential sqlite-tools

CMD ["go", "run", "."]