FROM alpine
WORKDIR mydir
ADD joke.sh /mydir
RUN chmod +x /mydir/joke.sh
RUN apk add curl
CMD ./joke.sh



