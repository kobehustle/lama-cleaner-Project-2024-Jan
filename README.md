# Install and Demo Lama Clearner A-Z

## Setup
- General
  - [VirtualBox Download](https://www.virtualbox.org/wiki/Downloads) VirtualBox-7.0.12-159484.exe 
  - [Ubuntu 22.04.3 LTS Download](https://ubuntu.com/download/desktop) Ubuntu 22.04.3 LTS
- Ubuntu Setting
  - Setting Sufficient Memory and Processors
  - Enough Storage (over 30GB) for installing lama-cleaner inside
- In Ubuntu Setting
  - Install git
  - Install python
 
## Install lama-cleaner with conda
#### Installing conda
- In terminal, with codes
  - $ wget https://repo.anaconda.com/archive/Anaconda3-2022.10-Linux-x86_64.sh
  - $ bash Anaconda3-2022.10-Linux-x86_64.sh
  - Restart the terminal
#### Installing lama-cleaner
- - [Installing lama-cleaner](https://www.linuxlinks.com/machine-learning-linux-lama-cleaner-self-hostable-inpainting-tool/) 
  - $ conda create --name lama-cleaner
  - $ conda activate lama-cleaner
  - $ pip install lama-cleaner
- +(if needed)Install plugins
  - $ pip install rembg
  - $ pip install realesrgan
  - $ pip install gfpgan

## Start lama-cleaner
- In terminal, with codes
  - $ lama-cleaner --model=lama --device=cpu --port=8080
- Using lama-cleaner
  - Point your web browser at http://127.0.0.1:8080
