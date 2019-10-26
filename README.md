#### Workshop by the UNB Developer Society
Intro to Computer Vision and Machine Learning
-----

### Environment Setup
#### Windows
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
6. While your virtual environment is active, run the command `$ pip install --upgrade tensorflow` 
##### Part 4 -- Install the Jupyter Digital Notebook
7. In you virtual environment, run the command `$ python3 -m pip install jupyter`
8. To activte your notebook, run the command `$ jupyter notebook`
