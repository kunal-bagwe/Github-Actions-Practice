FROM golang:1.12-alpine
RUN mkdir /server
WORKDIR /server
COPY . .
EXPOSE 8080
CMD ["go","run","main.go"]
