# mika assistant (with chatgpt integration)

## Installation

### Linux

For the installation on linux you can run the shell script to install python, pip and the required packages.

Step 1. 
Clone the repo and cd into it

```bash
git clone https://github.com/Mika-Project/mika-assisstant.git 
cd mika-assistant
```

Step 2.
Run the shell script, this will download all the required packages.

```bash
chmod +x install-requirements.sh 
sh install-requirements.sh
```

NOTE: This script works on Arch and Debian based distros! (For other distros you can for the most part follow the windows guide.)

Step 3.
Run the Python script.

```bash
python3 script.py
```

The script should run fine without any errors.

---

### Windows

Step 1.
Make sure to install python and pip from the [official website,](https://www.python.org/downloads/) during the installation make sure to tick the box for adding python to path.

Step 2.
CD and glone the github repo. (You can also download from the releases tab.)

```bash
git clone https://github.com/Mika-Project/mika-assisstant.git ; cd mika-assistant
```

Step 3.

Download the required pip packages.

```bash
pip install -r requirements.txt
```

Step 4.
Run the Python script.

```bash
python3 script.py
```

The script should run fine without any errors.


## Info

When the script runs a window will pop up, this is the GUI. Since it's technically an webserver you can also access it from `http://localhost:8000/`. But the UI is not made for that usecase, and we do not offer support if anything happens in that state.
