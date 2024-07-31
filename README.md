# how to setup a jupyter notebook
## install homebrew / wsl

https://brew.sh/
https://learn.microsoft.com/en-us/windows/wsl/install

## install python on homebrew
```
❯ brew install python3
```

## install python on WSL
```
❯ sudo apt update 
❯ sudo apt upgrade -y
❯ sudo apt install python3
```
## if python3-venv is not installed together with python3
```
❯ sudo apt install python3-venv 
```
## create venv
```
❯ python3 -m venv MyProject
```
### This will create a directory called MyProject under the current directory
```
❯ ls -l MyProject 
total 8
drwxr-xr-x  12 jaehkim  staff  384 31 Jul 16:26 bin
drwxr-xr-x   3 jaehkim  staff   96 31 Jul 16:26 include
drwxr-xr-x   3 jaehkim  staff   96 31 Jul 16:26 lib
-rw-r--r--   1 jaehkim  staff  293 31 Jul 16:26 pyvenv.cfg

~ 
❯ 

```
## activate the virtual environment
```
❯ source ./MyProject/bin/activate
```
### python3 is now under venv directory created earlier
```
❯ which python3
/Users/jaehkim/MyProject/bin/python3
```

## install jupyter notebook
```
❯ pip install notebook
```

## run jupter notebook 
```
❯ jupyter notebook   
```

## once browser session is launched, open .ipynb files
