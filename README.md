# wsl-vscode-tutorial
ref: [Install TensorFlow with pip](https://www.tensorflow.org/install/pip)
## 1. installation wsl
1.1 open cmd
wsl --install Ubuntu

## 2. install miniconda3
- curl https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -o Miniconda3-latest-Linux-x86_64.sh
- bash Miniconda3-latest-Linux-x86_64.sh

## 3. install VSCode's extension
- WSL
- Remote SSH
- Jupyter
- Python

## 4. tensorflow
- `sudo apt update`
- `sudo apt install build-essential`
- `sudo apt-get install manpages-dev`
- check version if install successfully `gcc --version` [ref](https://linuxize.com/post/how-to-install-gcc-on-ubuntu-20-04/)
- `pip install -q tf-models-official==2.11.0`

## Additional
### limit memory usage
- create .wslconfig by type script in cmd
- `editor "$(wslpath "C:\Users\<YourUsername>\.wslconfig")"`
```
[wsl2]
memory=4GB
```
- Restart wsl
```
wsl --shutdown
```
