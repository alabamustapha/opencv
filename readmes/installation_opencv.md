# OpenCV For beginners

### Installing Python
1. Download python from the python website
2. locate downloaded file, and install
choose the add to path option
3. Open cmd, type python and see if the interpreter comes up.


It is advisable to create python environment for each project, also each project can require different python version. To create multiple python executable:

1. You can follow this guide [here](https://levelup.gitconnected.com/how-to-install-and-manage-multiple-python-versions-on-windows-10-c90098d7ba5a)

Or
 
2. After downloading multiple python versions you can run each version like
`py -3.9 xxxxxxx`

### Virtual Environment
To manage all your opencv project and other projects it is advisable to create a virtual environment.

make a separate folder for your project and create a virtual environment with the steps below

1. Open cmd and make sure you are in the project folder directory 
2. enter this command python -m venv opencv-env
3. If you want to use a specific python version you can use this format 
`py -3.9 -m venv opencv-env` 3.9 is the python version and opencv-env is the name we want to call our environment

4. the opencv-env can be any name, after you press enter a virtual environment folder will be create, to enter this environment you need to activate it 
5. To activate, from the project folder run the activate script with
`.\opencv-env\Scripts\activate`

6. the terminal will have the environment name shown before the directory if successfull. All plugins installed will only affect this project and not your entire system

### Installing Packages
All commands should be run from the environment by:
1. open cmd
2. cd into you project folder
3. activate your environment 
4. Run all codes in the environment.

Upgrade pip to avoid warnings and error

`python -m pip install --upgrade pip`

using pip, you will need to install the following packages

1. [opencv-contrib-python](https://pypi.org/project/opencv-contrib-python/)
2. [jupyter](https://pypi.org/project/jupyter/) 
3. [streamlit](https://pypi.org/project/streamlit/)
3. [moviepy](https://pypi.org/project/moviepy/) 
4. [ipykernel](https://pypi.org/project/ipykernel/) 
5. [matplotlib](https://pypi.org/project/matplotlib/)

You should also install the following optional packages

1. [pyautogui](https://pypi.org/project/PyAutoGUI/)
2. [mediapipe](https://pypi.org/project/mediapipe/) (python 3.7, 3.9 required to use pip install mediapipe)
3. [mime](https://pypi.org/project/mime/)
