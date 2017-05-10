hello-world
===========

## Swarm

	docker stack deploy --compose-file docker-stack.yml hello
	docker stack services hello
	docker service scale hello_app=10

[http://app.test.com/](http://app.test.com/)
[http://www.test.com/](http://www.test.com/)
[http://localhost:1936/](http://localhost:1936/)


## Swarm with Traefik

	docker stack deploy --compose-file docker-traefik.yml traefik
	docker stack services traefik
	docker service scale traefik_app=10
