# auto-recording
Hi! I am totally fresh to github, English, and even deep learning. My thesis topic is auto-recording. So, let's play with it. I want to develop a system to finish auto-recording, and the related work will be object detection, tracking, gesture recognition, facial expression detection. 

## Installing tensorflow on linux
see https://www.tensorflow.org/install/pip

1.Requires Python > 3.4 and pip >= 19.0

python3 --version
pip3 --version
virtualenv --version
I update pip3, however there is a problem: pip ImportError: cannot import name 'main' after update
Thanks for google, I solved it.  hash -d pip3 works for me.


2.Create a virtual environment
Each time I want to activate it, I can use: source ./venv/bin/activate  # sh, bash, ksh, or zsh
To exit, just deactivate.
Ok, successfully install tensorflow-gpu

## Installing pytorch on linux
see PyTorch.org and choose configuration of your PC.
I installed PyTorch by using : pip3 install torch torchvision, and still installed it on virtual environment.
