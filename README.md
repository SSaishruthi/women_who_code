# Women who Code - workshop


The code here was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

The packages needed to run the code in the notebooks are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).

## 1) Download this file: 

- [requirements.txt](requirements.txt)

## 2) Install the packages:

### If you are using [Anaconda](https://www.anaconda.com/)

=> Install without creating a stand-alone environment (virtual env):

To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

=> Install creating a stand-alone environment (virtual env) (SUGGESTED)

1) To create a stand-alone environment named ``women-who-code`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n women-who-code python=3.5 --file requirements.txt
```
2) Activate the environment

```
$ source activate women-who-code
```
3) After you are done working on this, you can deactivate

```
$ conda deactivate
```


You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.

### If you are not using Anaconda

=> Install without creating a stand-alone environment (virtual env):

```
pip install -r requirements.txt 
```

=> Install creating a stand-alone environment (virtual env):

To create a virtual environment, go to your project’s directory and run virtualenv.

On macOS and Linux:

```
python3 -m virtualenv women-who-code
```

On Windows:
```
py -m virtualenv women-who-code
```

The second argument is the location to create the virtualenv. Generally, you can just create this in your project and call it env.

Before you can start installing or using packages in your virtualenv you’ll need to activate it. Activating a virtualenv will put the virtualenv-specific python and pip executables into your shell’s PATH.

On macOS and Linux:

```
source women-who-code/bin/activate
```


## License

### Code
The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

