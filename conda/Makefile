compile:
	conda activate conda-build && conda-build -c conda-forge . --keep-old-work --python 3.10.4

debug:
	conda activate conda-build && conda-debug -c conda-forge . --python 3.10.4

install:
	conda env create -f environment.yml

update:
	conda env update -n conda-build --file environment.yml --prune