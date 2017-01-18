# FeatureFactory


## Requrements

The package has the following dependencies:

* jupyter
* matplotlib
* numpy
* mysqlclient
* mysql-connector-python-rf
* pandas
* scikit-learn
* scipy
* sqlalchemy
* sqlalchemy_utils

These dependencies can be installed using pip with the following command:
```
pip install -r requirements.txt
```

Otherwise, they will be collected and installed anyway during setup by setuptools, but this
process much slower than using pip, if it suceeds at all.

## Setup

The package needs to be installed from withing src folder using setup.py

```
cd src
python setup.py install
```

## Usage

Once it the package is installed, the `orm.admin.Commands` class can be used to initiate
the DB environment and register the problems.
The Jupyter Notebooks found in `notebooks/admin` folder contain some usage examples.

After the environment is set-up, a Jupyter notebook instance needs to be started from within
the problem folder, inside the `notebooks` dir.
