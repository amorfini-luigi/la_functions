# la_functions

My Library Personal from Python 3

# setup

python -m venv venv

./venv/Scripts/activate.ps1

python -m pip --no-cache-dir install -U pip setuptools 

pip --no-cache-dir install wheel

# lib

pip --no-cache-dir install guizero pillow requests numpy sounddevice soundfile

# la_functions

cls

cd libs/la_functions

python setup.py build

python setup.py sdist

pip install .\dist\la_functions-0.1.0.tar.gz

cd .. ; cd ..

cls
