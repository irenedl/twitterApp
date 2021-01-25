# twitterApp
This is very simple NGINX website that allows a user to send a tweet. 

It's mostly used as a sample application for Docker or Kubernetes.

To use it:

Build it:
`docker build -t idl444/twitterapp .`

Run it:
`docker container run --detach -p 80:80 idl444/twitterapp`
