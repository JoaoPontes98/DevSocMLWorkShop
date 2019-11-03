#### Workshop by the UNB Developer Society
Intro to Computer Vision and Machine Learning
-----

### Environment Setup
#### Windows
#### Installing Python
* You can download an installer for the most recent Python3.7 version here: [Python 3.7.5 install](https://www.python.org/downloads/release/python-375/) (32bit Python versions as well as Python 3.8.x is not supported by Tensorflow)
* Once the download has completed run the installer
* When prompted select the check the box for "Add Python3 3.7 to Path"s
* When prompted click on the option to change the MAX_LENGTH for Paths on your machine
#### Creating a Virtual Environment
The first step to starting any Python3 project is creating a virtual environment. This allows us to keep our installs for different projects seperated.
* Make a directory for the workshop project `> mkdir ml-workshop`
* Create a virtual environment in your project folder `> python -m venv workshop-env`
* Activate your new virtual environment `> .\workshop-env\Scripts\activate`

#### Installing Packages
Within the virtual environment we can then install Tensorflow 2.0, with the virtual environment active we can run `> pip install tensorflow`

We will also want to install Pillow for viewing the images that we will be training the computer to identify, we can install Pillow with the following command `> pip install Pillow`

You may have to updgrade your pip version before you can install Tensorflow 2.0, this can be done with `> python -m pip install --upgrade pip`

#### Install Jupyter Notebook (recommended)
I'll be using Jupyter Notebook as a code editor for this tutorial, I would recommend you install and use it as well however you may use any IDE/code editor of your choice. To install Jupyter Notebook run the following command with the virtual environment activated
`> pip install jupyter`

Once you have jupyter installed you can begin running it by entering the command `> jupyter notebook`

#### UNIX (Mac/Linux)
##### Part 1 -- Installing Python
1. Download [HomeBrew](https://brew.sh/#install) package manager. 
  - To install it, run the command `$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  - Homebrew is a package manager that stream lines the setup of developer technologies on Mac. In this case, we will use         homebrew to install python 3
2. Confirm if you installed Homebrew correctly by running the command `$ brew doctor`
3. To install python, run the command `$ brew install python3`
4. Now confirm if python was installed correctly by running `$ python --version`
  - If you ran into any problems while installing python on to, there are plenty of resources online to help 
##### Part 2 -- Creating a virtual environment 
5. To create a virtual environment, run the command `$ python3 -m venv <directory_name>-env`. Replace <directory_name> with what you would like you virtual environment directory to be called.
6. To activate the virtual environment, run the command `$ source <directory_name>/bin/activate`. 
  - You know your virtual environment is properly activated when you see (<directory_name>) at the beginning of your command line.
##### Part 3 -- Installing Tensor Flow
THE FOLLOWING STEPS COULD BREAK YOUR OS IF NOT DONE ON A VIRTUAL ENVIRONMENT

6. While your virtual environment is active, run the command `$ pip install --upgrade pip` 
7. While your virtual environment is active , run the command `$ pip install tensorflow` 
##### Part 4 -- Install the Jupyter Digital Notebook
8. In your virtual environment, run the command `$ pip install jupyter`
9. To activte your notebook, run the command `$ jupyter notebook`
##### Part 5 -- Install Pillow
10. In your virtual environment, run the command `$ pip install Pillow`
