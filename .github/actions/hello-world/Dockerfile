FROM golang:latest
WORKDIR /go/src/hello
COPY . .
RUN go env -w GO111MODULE=auto
RUN go get -d -v ./...
RUN go install -v ./...
CMD ["hello"]