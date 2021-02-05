Load approporate module for your python virsion. I like to use python 3.7 now.
```
module load eb/2019 Anaconda3
python --version
```
This returns `Python 3.7.4`.


Be in the directory where you want to create a virtual environment.
```
cd dir_to_create_env
```

Create an environment named .venv which is invisible.
```
python -m venv .venv
```

Then, activate.
```
source .venv/bin/activate
```

Install your packages such as matplotlib.
```
python -m pip install matplotlib --ignore-installed
```
