# Multimodal learning
First, [download Miniconda](https://conda.io/miniconda.html), or install it using your 
packaging system.

Then, set up a vritual env to install the dependent packages into:

```commandline
# update pip to the latest version
pip install --upgrade pip
# create virtual env
conda create --name multimodal python=3.6
# activate a new environment
source activate multimodal
# install requirements to newly-created env
pip install -r requirements.txt
# or install any other packages that you would need, inside the activated environment, using 'pip install <package>'
```

Make sure to include the dependencies that you'd install locally into requirements.txt. You can just copy the name of the library that you install using pip.

### Resources:

[9.5. meeting notes](https://docs.google.com/document/d/1asq5LpirCd76nbM4B01lf5Mkl4MHBOsUfat7PiMrAtI/edit?usp=sharing)

[trelo dashboard](https://trello.com/b/dajXkcG2/uvod-do-ml)

[Google's word2vec model (1.5GB)](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit)
