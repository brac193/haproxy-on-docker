Simple demonstration of HAProxy load balancer using Docker containers and NodeJS as backend server.
HAProxy is using roundrobin for switching between node's.

If you want to run it install Docker and Docker-Compose and then from project's root run:

```docker-compose up -d```

To test run a few times:

```curl localhost:8080```

and you should see that traffic is divided by 2 servers.
