# Probabilistic/Statistical Machine Learning

Please use the **dedicated forum on moodle** for questions on theory and exercises.

If you notice some errors in the notebooks/homeworks contact me at: **<name@phd.units.it>** (name=ginevra.carbone)
	
## Utils

- [Stackexchange](https://stackexchange.com/)
- [Github guide](https://guides.github.com/activities/hello-world/)
- [Virtualenvs in python3](https://docs.python.org/3/library/venv.html)
- [Beginners numpy tutorial](http://cs231n.github.io/python-numpy-tutorial/)
- [Beginners pandas tutorial](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/)
- [Pyro 1.2.1 documentation](http://docs.pyro.ai/en/1.2.1/)

## Linux Setup

Python version: 3.6.9

Download, clone or fork (your choice) this repository in a directory `PATH_TO_DIR/`.

Create a virtual environment using `python3` (commands are provided for *Debian-like* GNU/Linux distributions)
```
sudo apt install -y python3-venv
cd PATH_TO_DIR/statistical-machine-learning/
python3.6 -m venv venv
```

Now you should see `PATH_TO_DIR/statistical-machine-learning/venv/` folder.
Activate the enviroment and install the requirements:
```
source venv/bin/activate
pip install -r basic_requirements.txt
```

Register the just-installed virtual environment for use with Jupyter:
```
python3 -m ipykernel install --user --name statistical-machine-learning --display-name "Python (SML virtualenv)"
```

Open your notebooks using jupyter-notebook (or jupyter-lab):
```
python3 -m jupyter notebook
```

To deactivate the environment use `source deactivate` command.
