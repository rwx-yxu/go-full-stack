FROM golang:1.17-alpine

WORKDIR /app

COPY ./go.mod .

RUN go mod download

COPY . .
CMD ["go", "run", "main.go"]