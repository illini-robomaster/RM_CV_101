# Python Installation Help for Newcomers

## MacOS (no CUDA)

### Install with package manager (Recommended)

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

### Install with Anaconda (Not recommended)

As an alternative, it's also possible to install python3 and jupyter with Anaconda.
However, Anaconda is not a flexible choice since there are a lot of packages
that do not reside in Anaconda. You may end up having to install multiple
Python3 instances on your machine.

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

TODO

## PyTorch

https://pytorch.org/get-started/locally/
