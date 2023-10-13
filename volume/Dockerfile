FROM golang:1.18-alpine
ENV APP_PORT=8080
ENV APP_DATA=/logs

RUN mkdir ${APP_DATA}
RUN mkdir app
COPY app/main.go app

EXPOSE ${APP_PORT}
VOLUME ${APP_DATA}
CMD go run app/main.go