# Hands-On-Machine-Learning-With-Scikit-Learn-And-Tensorflow
My work to go along with the book ["Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems"](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291). 

My work will be broken down by chapter. Each chapter will have a respected folder, with a `README.md` for more information. Generally, I'll use Jupyter Notebooks and Python, leveraging virtual environments to capture dependencies.

## Virtual Environments

### Creating

In the folder you wish to create the virtual environment, run

`$ python -m venv [NAME]` 

_I like to use "venv" for the name_

### Activating

run 

`$ source venv/bin/activate`

#### Installing Dependencies

While activated, run

`$ pip3 install [PACKAGE NAME]`

#### Freezing Local Dependencies

While activated, run

`$ pip3 freeze --local > requirements.txt` 

_we specify `--local` to ensure no globally installed packages accidentally squeek their way in_

#### Creating A Jupyter Notebook Kernel

While activated, run

`$ pip3 install ipykernel`

and then

`$ ipython kernel install --user --name=[PROJECT NAME]`

### Deactivating

run

`$ deactivate`

