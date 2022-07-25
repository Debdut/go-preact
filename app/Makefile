all: build

##@ Development

init: 
	npm install

lint:  ## Lint preact files
	npm run lint

test:  ## Test preact files
	npm run test
	
##@ Build

build: init lint test
	npm run build

clean:
	rm -rf build node_modules size_plugin.json
