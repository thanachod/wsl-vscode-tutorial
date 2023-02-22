# wsl-vscode-tutorial
ref: [Install TensorFlow with pip](https://www.tensorflow.org/install/pip)
## 1. installation wsl
1.1 open cmd
wsl --install Ubuntu

## 2. install miniconda3
2.1 curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -o Miniconda3-latest-Linux-x86_64.sh
2.2 bash Miniconda3-latest-Linux-x86_64.sh

## 3. install VSCode's extension
3.1 WSL
3.2 Remote SSH
3.3 Jupyter
3.4 Python
## Additional
### limit memory usage
1. create .wslconfig by type script in cmd
- editor "$(wslpath "C:\Users\<YourUsername>\.wslconfig")"
```
[wsl2]
memory=4GB
```
2. Restart wsl
```
wsl --shutdown
```
