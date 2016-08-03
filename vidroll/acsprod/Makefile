DOCKER_IMAGE_NAME=vidroll/acsprod-datadog:latest

build: Dockerfile
	docker build -t ${DOCKER_IMAGE_NAME} .

push: build
	docker push ${DOCKER_IMAGE_NAME}

