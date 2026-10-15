PROJECT_ID = eceb4063-096c-4280-bcbc-5ea1704d8512
DC = infisical run --projectId=$(PROJECT_ID) --env=dev -- docker compose

.PHONY: up down restart config logs ps pull

up:
	$(DC) up -d

down:
	$(DC) down

restart:
	$(DC) up -d --force-recreate

config:
	$(DC) config -q

logs:
	$(DC) logs -f --tail=100

ps:
	$(DC) ps

pull:
	$(DC) pull
