GOCMD=go
GOBUILD=$(GOCMD) build

all: project

build-windows:
	GOOS=windows GOARCH=amd64 $(GOBUILD)

project: *.go
	$(GOBUILD) -v
