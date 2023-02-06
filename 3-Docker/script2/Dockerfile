FROM alpine:3.12

WORKDIR /app

COPY main.sh .

RUN echo "contrasena" > passwords.txt

RUN chmod +x main.sh

RUN ./main.sh