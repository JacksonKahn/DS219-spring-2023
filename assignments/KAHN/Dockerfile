FROM alpine

RUN apk add --no-cache \
    python3 \
    py3-pip

WORKDIR /KAHN

COPY hello-world.py .

RUN chmod +x hello-world.py

CMD ["python3", "hello-world.py"]
