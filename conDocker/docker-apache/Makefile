GIT_TAG := $(shell git rev-parse --short HEAD)
# con el comando lo que hacemos el devolver el ultimo commit
# y eso lo pasamos al build para etiquetar la imagen

build_and_tag: build tag
build:
	docker build -t hybridaccess:$(GIT_TAG) .

tag:
	docker tag hybridaccess:$(IMAGE_NAME) hybrid:latest
