# Simple tasks

build:
	echo "renaming all *.example files in this directory..."
	@make remove_examples

remove_examples:
	mv ./.env.example ./.env
	mv ./traefik.toml.example ./traefik.toml

check:
	docker-compose config