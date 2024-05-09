typehint:
	mypy --ignore-missing-imports src/

test:
	pytest tests/

lint:
	pylint src/

checklist: lint typehint test

black:
	black -l 79 *.py

setup:
	pip install -r requirements.txt

.PHONY: typehint test lint checklist black
