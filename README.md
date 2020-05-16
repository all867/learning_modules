# Learning modules
This repo contains a collection of learning modules that I have created, largely with Jupyter notebooks. The modules are grouped into files by domain, where   

- `cmse` = computational materials science and engineering


## Usage
Most of the Jupyter notebooks have an interactive component that requires dynamic rendering. There are several ways to do this, and I give two below:

### 1: Google Colaboratory
This method is nice because it doesn't require you to have Git or Python on your computer, and you can save a copy of each notebook on your Google account.   

1. Click through the GitHub repo until you've found the notebook you want to render.   
1. Go to https://colab.research.google.com and click `File > Open notebook > GitHub`.   
1. Copy and paste the file URL from this repo into the blank space and you should be able to run the notebook.

### 2: Cloning the repo
If you're familiar with GitHub and have Python installed on your computer, this is another option.   

1. Clone the repo.   
1. Install the libraries in `requirements.txt` so that you can run all the notebooks. You can do this with:
    ```bash
    pip install -r requirements.txt 
    ```   
1. Load Jupyter (`jupyter notebook`) and run the notebooks.   


## Acknowledgements
By sharing this repo publicly on GitHub under a [MIT license](LICENSE), I'm pretty much giving you free rein to do whatever you wish with the code. If you found the modules helpful, do spread the word to your friends/classmates, and a shout-out would be appreciated. If you need a more formal citation, something like the following could work:   

```
Enze Chen, Learning modules, (2020), GitHub, https://github.com/enze-chen/learning_modules.
```
or in BibTeX:   

```
@misc{Chen2020,
    author = {Chen, Enze},
    title = {Learning modules},
    year = {2020},
    publisher = {GitHub},
    howpublished = {\url{https://github.com/enze-chen/learning_modules}},
}
```

## Contributing
If you have any questions about any of these modules or have an idea for a new module, please let me know!