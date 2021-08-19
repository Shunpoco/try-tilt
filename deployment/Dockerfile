FROM golang:1.17

WORKDIR /app

ADD . .

RUN go install ./

ENTRYPOINT tilt-example-go
