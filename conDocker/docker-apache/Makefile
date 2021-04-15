IMAGE_NAME := $(shell git rev-parse --short HEAD)
# con el comando lo que hacemos el devolver el ultimo commit
# y eso lo pasamos al build para etiquetar la imagen

build:
	docker build -t hybridaccess:$(IMAGE_NAME) .

tag:
	docker tag hybridaccess:$(IMAGE_NAME) hybrid:latest
