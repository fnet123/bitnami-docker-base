all: build

build:
	@docker build --tag=bitnami/base-ubuntu:14.04-buildpack .
	@$(MAKE) -C onbuild $@

