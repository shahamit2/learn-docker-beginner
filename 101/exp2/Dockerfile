FROM alpine:3.14
RUN mkdir -p '/quotes'
#RUN apk add --no-cache mysql-client
WORKDIR '/quotes'
COPY quote.txt .
CMD ["cat", "quote.txt"]