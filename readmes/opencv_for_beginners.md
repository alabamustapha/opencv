# OpenCV For beginners

### Installing Python
Download python from the python website
locate downloaded filfe, and install
choose the add to path option
open cmd, type python and see if the interpreter comes up.

create multiple python executable 
https://levelup.gitconnected.com/how-to-install-and-manage-multiple-python-versions-on-windows-10-c90098d7ba5a

afterdownloading multiple python versions you can run each version like

py -3.9 xxxxxxx

### Virtual Environment
To manage all your opencv project and other projects it is advisable to create a virtual environment.

make a separate folder for your project and create a virtual environment with the set below

1. Open cmd and make sure you are the project folder directory 
2. enter this command python -m venv opencv-env (py -3.9 -m venv opencv-env)
3. the opencv-env can be any name, after you press enter a virtual environment folder will be create, to enter this environment you need to activate it 
4. to activate, run the script .\opencv-env\Scripts\activate
5. the terminal will have the environment name shown before the directory if success. all plugins installed will only affect this project and not your entire system
### Installing Packages
Upgrade pip to avoid warnings and error

`python -m pip install --upgrade pip`

using pip, you will need to instal the following packages

1. opencv-contrib-python
2. jupyter 
3. moviepy 
4. ipykernel 
5. matplotlib

You should also install the following optional packages

1. pyautogui
2. mediapipe (python 3.7, 3.9 required to use pip install mediapipe)
3. mime
