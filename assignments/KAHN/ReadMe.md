*Jackson Kahn Container Assignment ReadMe File*

The script that I have enclosed within my container is called hello-world.py, 
and it is a simple python script which prints "hello world". 

Building the container image can be done through the command:
podman build -t docker.io/accountname/hello-world -f Dockerfile .

Running this image can be done through the command:
podman run hello-world



