  
DOCKER ?= docker
TARGET ?= nanopi/novnc-winbox

all:
	@echo "Building ${TARGET}"
	$(DOCKER) build -t $(TARGET) -f Dockerfile .

