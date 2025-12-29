SRC = hello-world.hs
EXE = build/hello-world
BUILD_DIR = build

all: build

build:
	mkdir -p $(BUILD_DIR)
	ghc -O2 -Wall -o $(EXE) $(SRC) -outputdir ${BUILD_DIR}

run:
	runghc $(SRC)

.PHONY: run build
