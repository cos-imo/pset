.PHONY:
	run module

run:src/core/__main__.py
	@python3 -m src.core 

paths:
	export PYTHONPATH=src pytest tests/

module1:
	@python3 -m src.modules.module1

module2:
	@python3 -m src.modules.module2

modules:
	module1
	module2

clean:
	pass
