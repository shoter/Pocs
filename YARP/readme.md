# Yet Another Reverse Proxy - Load Balancer PoC

This PoC was created to see how to create load balancer using
[YARP](https://microsoft.github.io/reverse-proxy/).

It is a simple load balancer which accepts requests at localhost:11080/test/ and
redirects the request to 1 of 2 service APIs.
