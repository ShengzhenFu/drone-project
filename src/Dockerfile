FROM public.ecr.aws/docker/library/golang:1.22.3-alpine

WORKDIR /usr/src/app

COPY go.mod ./
RUN go mod download

COPY . .
RUN go build -v -o /usr/local/bin/app ./...

EXPOSE 5000
CMD ["app"]
