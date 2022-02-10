FROM golang:1.16

RUN git clone https://github.com/docker-hy/material-applications.git
WORKDIR /go/material-applications/example-backend
RUN go build
EXPOSE 8080

CMD ./server