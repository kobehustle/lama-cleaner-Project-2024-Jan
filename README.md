# Install and Demo Lama Clearner A-Z

## Setup
- General (Latest version of VirtualBox and Ubuntu)
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
  - `$ wget https://repo.anaconda.com/archive/Anaconda3-2022.10-Linux-x86_64.sh`
  - `$ bash Anaconda3-2022.10-Linux-x86_64.sh`
  - Restart the terminal
#### Installing lama-cleaner
- In terminal, with codes
  - `$ conda create --name lama-cleaner`
  - `$ conda activate lama-cleaner`
  - `$ pip install lama-cleaner`
- +(if needed)Install plugins
  - `$ pip install rembg`
  - `$ pip install realesrgan`
  - `$ pip install gfpgan`


Refer site: [Installing lama-cleaner](https://www.linuxlinks.com/machine-learning-linux-lama-cleaner-self-hostable-inpainting-tool/) 


## Start lama-cleaner
- In terminal, with codes
  - `$ lama-cleaner --model=lama --device=cpu --port=8080`
- Using lama-cleaner
  - Point your web browser at http://127.0.0.1:8080
- Quit lama-cleaner
  - `CTRL + C`
 

Refer site: [Starting lama-cleaner](https://www.linuxlinks.com/machine-learning-linux-lama-cleaner-self-hostable-inpainting-tool/2/) 

# Using lama-cleaner

## Upload a picture
- Click `Tap here to load your picture`
  - All Supported Types: PNG image, JPEG Image
  - Choose the size of brush
  - Brush the parts of image you want to clean and wait a second
  - You can see the picuture without objects you brushed
![First page]([Imgaes/UI screenshot.png](https://github.com/kobehustle/lama-cleaner-Project-2024-Jan/blob/11eb8cb6df716d68dba266b3f274225f3d9a1f60/Imgaes/UI%20screenshot.png)https://github.com/kobehustle/lama-cleaner-Project-2024-Jan/blob/11eb8cb6df716d68dba266b3f274225f3d9a1f60/Imgaes/UI%20screenshot.png)
