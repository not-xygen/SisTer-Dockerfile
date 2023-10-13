FROM golang:1.18-alpine

RUN mkdir /app

RUN addgroup -S xploratech
RUN adduser -S -D -h /app xygen xploratech
RUN chown -R xygen:xploratech /app
USER xygen

COPY main.go /app

EXPOSE 8080
CMD go run /app/main.go