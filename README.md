### Fashion Digital SRE Interview

This repository contains a small docker-compose setup, containing of 3 docker images: 2 python app servers and an nginx load balancer. The load balancer is supposed to terminate SSL and forward traffic to the web servers.

The goal is to be able to browse to `https://localhost`, accept a self-signed certificate and observe the expected [output](output.png), alternately served by app1 and app2.

The setup contains a few - actually a ton - of errors, and your task is to debug and fix all of them!
