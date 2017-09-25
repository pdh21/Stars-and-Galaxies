
# Stars-and-Galaxies
Example repository for the Stars and Galaxies workshop

Todays Tasks:
1. Install miniconda python
2. Install Jupyter notebook
3. Create an example notebook
4. Create Github account
5. Upload example notebook to Github repository

## 1. Installing miniconda
`wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh`

`bash Miniconda3-latest-Linux-x86_64.sh`

## Fix to install
first get your current directory using command `pwd`. It should look something like this;
`-bash-4.2$ pwd

/home/p/pd/pdh21
`

Then open .bash_profile with `emacs .bash_profile` and add the following:

`export PATH="/home/p/pd/pdh21/miniconda3/bin:$PATH"
`
## Install jupyter

`conda install jupyter`
