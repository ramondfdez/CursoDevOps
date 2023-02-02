FROM alpine:latest as builder
RUN apk --no-cache add build-base

FROM builder as build1
COPY source1.cpp source.cpp
RUN g++ -o /binary source.cpp
CMD ["./binary"]
