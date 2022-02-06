FROM ubuntu:20.04

WORKDIR /curl-dir
RUN apt-get update && apt-get install -y curl

COPY curl-website.sh .
CMD ["/curl-dir/curl-website.sh"]