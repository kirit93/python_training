# Welcome to Python for Data Science!

This repo holds the Python notebooks and other files needed for this training. 
We'll be covering Pandas, specifically -
* Loading and saving data to and from DataFrames
* Dataframe manipulations
* Data descriptions and aggregations
* Grouped aggregations
* Sorting and filtering
* Table joins
* Advanced statistical methods
* Transforming dataframes
* Visualizing data

## Prerequisites

* Create Authentication Tokens for GitHub
    * GitHub authentication can happen via SSH keys or PATs (Personal Access Token)
        * [PAT](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token)
        * [SSH](https://docs.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
* Clone the repo
    * `git clone https://github.com/kirit93/python_training.git`
    * *Note* if you've setup your GitHub account with 2FA, you will need to use your PAT to authenticate. If not, your username and password will suffice.
* Python3 Installation
* Python3 virtualenv / anaconda environment setup
    * [venv](https://docs.python.org/3/library/venv.html)
        * Run the following command
            * `python3 -m venv /path/to/new/virtual/environment`
    * [Anaconda](https://docs.anaconda.com/anaconda/install/)
        * Follow the instructions to install anaconda depending on your OS
        * Run the following commands
            * `conda create -n /path/to/new/virtual/environment`
            * `conda install -n <NAME OF VIRTUAL ENV> pip`
* Install all the packages in `requirements.txt`
    * Activate your virtual environment
        * venv
            * `source activate /path/to/new/virtual/environment`
        * anaconda
            * `conda activate <NAME OF VIRTUAL ENV>`
    * Run this command to install all the required packages
        * `pip install -r requirements.txt`

*Note* 
* virtualenv works great for Python environments (on Mac, Linux), if you are on a PC, anaconda would be best. 
