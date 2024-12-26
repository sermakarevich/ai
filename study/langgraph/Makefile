SERVICE=default

env-create:
	conda env create -f environment.yml
env-create-dry:
	conda env create -f environment.yml --dry-run
env-update:
	conda env update -f environment.yml --prune
env-remove:
	conda env remove --name ${SERVICE}
env-export:
	conda env export > environment_export.yml
jupyter-kernel:
	python -m ipykernel install --user --name=${SERVICE} --display-name=${SERVICE}
