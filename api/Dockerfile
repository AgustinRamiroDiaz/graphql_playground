FROM golang:buster

WORKDIR /app
ADD . .

RUN go get github.com/cosmtrek/air
RUN go get github.com/99designs/gqlgen

RUN go install .

EXPOSE 8080
