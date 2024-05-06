How to Run Audio Processing Projects on Windows/Linux
This guide provides instructions on running the two Jupyter Notebooks you have for audio processing on Windows and Linux systems.

Prerequisites:

Python: Ensure you have Python 3.x installed. Download and install from the official website (https://www.python.org/downloads/) if you don't have it.
Jupyter Notebook: Install Jupyter Notebook using pip install jupyter. Open a terminal or command prompt and run the command.
Libraries: Both notebooks require specific libraries:
librosa: Install using pip install librosa.
matplotlib: Install using pip install matplotlib.
IPython (optional, for the second notebook's audio playback): Install using pip install ipython.

Running the Notebooks:

Open a Terminal/Command Prompt.

activate virtual environment which have prerequisites already installed.

If using windows:
    use : env\Scripts\activate.bat

if on linux :
    use: source env/bin/activate

after the virtual environment is activated: 

This command Starts Jupyter Notebook Server: Run the following command:

jupyter notebook

wait for the default browser to open up.

if nothing opens, go to this address manually : http://localhost:8888
