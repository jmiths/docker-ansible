To get the container up and running on localhost at port 32769, run: \
$ docker build -t ssh_test . \
$ docker run -d -P -p 32769:22 --name my_container ssh_test\
\
Make sure to use add your public key to the dockerfile
