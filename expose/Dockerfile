FROM golang:1.18-alpine

RUN mkdir app
COPY app/main.go app

EXPOSE 8080

CMD go run app/main.go