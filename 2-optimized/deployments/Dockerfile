FROM alpine:3.15
WORKDIR /app
ADD web web
ADD build build
ENTRYPOINT build/tilt-example-go
