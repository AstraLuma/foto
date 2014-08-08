PYVER=3.3
all :
	echo Please choose a target

.venv :
	pyvenv-$(PYVER) .venv
	echo Activate the virtualenv and then run make pip

pip :
	wget https://bootstrap.pypa.io/get-pip.py -O /tmp/get-pip.py
	python3 /tmp/get-pip.py
	pip install -r DEPS

.PHONEY : all pip