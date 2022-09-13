# Python Installation Help for Newcomers

## Install with Anaconda

Check out [this tutorial](https://www.datacamp.com/tutorial/installing-anaconda-windows) for installing Anaconda, [this tutorial](https://stackoverflow.com/questions/23119413/how-do-i-install-python-opencv-through-conda) for installing OpenCV, and [this tutorial](https://towardsdatascience.com/how-to-set-up-anaconda-and-jupyter-notebook-the-right-way-de3b7623ea4a) for installing Jupyter Notebook.

## MacOS (no CUDA)

Visit [brew.sh](https://brew.sh/) for the brew MacOS package manager
(note: you can use MacPorts instead but I personally recommend brew). Follow the instruction and install brew.
To pull up the terminal prompt in MacOS, you may do
(command + space) to invoke Spotlight search, then type "terminal".

After installing brew, get Python 3 from brew. Type the following
commands into your terminal
```
brew install python3
```

pip is a library management tool for Python. We will use pip through out the entire RMCV 101 training.
To get Jupyter Notebook (which is a helpful interactive programming tool
for Python programmers), type the following commands into your terminal
```
python3 -m pip install --upgrade pip
python3 -m pip install jupyter
```

Finally, get numpy and OpenCV
```
python3 -m pip install numpy
brew install opencv
```

## Debain/Ubuntu

Pull up terminal and put these commands in
```
sudo apt-get update
sudo apt-get install python3 python3-dev
sudo python3 -m pip install --upgrade pip
sudo python3 -m pip install jupyter
```

and follow [Official Installation Guide](https://docs.opencv.org/4.1.1/d7/d9f/tutorial_linux_install.html)
to build from source.

## Windows

I personally don't use Windows for programming, so I encourage you to either look into Anaconda for Windows or Ubuntu Subsystem for Windows. If anyone with Windows has any suggestion about setting up dependencies on Windows, feel free to open a PR/issue and you can contribute to RM_CV_101!

## PyTorch

Check out this [Get Started](https://pytorch.org/get-started/locally/) page from PyTorch official. If you used Anaconda, I recommend you follow instructions on this page and install everything with Anaconda.
