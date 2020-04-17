# Deploy Keras Model with Flask as Web App in 10 Minutes

[![](https://img.shields.io/badge/python-3.5%2B-green.svg)]()
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

> A pretty and customizable web app to deploy your DL model with ease


## Getting started in 10 minutes

- Clone this repo 
- Install requirements
- Run the script
- Go to http://localhost:5000
- Done! :tada:



## Local Installation

It's easy to install and run it on your computer.

```shell
# 1. First, clone the repo

$ cd Image Classifier

# 2. Install Python packages
$ pip install -r requirements.txt

# 3. Run!
$ python app.py
```

Open http://localhost:5000 and have fun. :smiley:


------------------

## Customization

It's also easy to customize and include your models in this app.

<details>
 <summary>Details</summary>

### Use your own model

Place your trained `.h5` file saved by `model.save()` under models directory.

Check the #L37 in app.py.

### Use other pre-trained model

See [Keras applications](https://keras.io/applications/) for more available models such as DenseNet, MobilNet, NASNet, etc.

Check [this section]#L26 in app.py.

### UI Modification

Modify files in `templates` and `static` directory.

`index.html` for the UI and `main.js` for all the behaviors.
