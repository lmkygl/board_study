DOCKER_COMPOSE_PROJECT_NAME = board-study

.PHONY:up
up:
	docker-compose -p ${DOCKER_COMPOSE_PROJECT_NAME} up -d

.PHONY:down
down:
	docker-compose -p ${DOCKER_COMPOSE_PROJECT_NAME} down

.PHONY:log
log:
	docker-compose -p ${DOCKER_COMPOSE_PROJECT_NAME} logs -f
