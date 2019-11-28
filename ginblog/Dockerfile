FROM golang:latest

ENV GOPROXY https://goproxy.cn,direct
WORKDIR $GOPATH/src/ginblog
COPY . $GOPATH/src/ginblog
RUN go build .

EXPOSE 8080
ENTRYPOINT [".ginblog"]