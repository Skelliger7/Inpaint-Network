# Object-Deletion

## Requirements and dependencies:


1.  Python3
```console
apt-get install python3.7-dev
```

2.  python3.7-pip 
```console
sudo apt-get install python3-pip
python3.7 -m pip install pip
```

3.  Pytorch
```console
sudo -H python3.7 -m pip install torch==1.2.0+cpu torchvision==0.4.0+cpu -f https://download.pytorch.org/whl/torch_stable.html
```
For GPU or other version: https://pytorch.org/get-started/locally/

4.  FastAI
```console
python3.7 -m pip install --user fastai
```

5.  Pillow-5.1.0
```console
python3.7 -m pip install --user -U Pillow
```

6.  OpenCV-4.1.1.26
```console
python3.7 -m pip install --user opencv-python
```

7.  Jupyter
```console
python3.7 -m pip install --user jupyterlab
sudo apt install jupyter-notebook
```

## Inference

Example:
```console
python3.7 main.py --image img.png
```

CLI Arguments:
* '--image' : Filename of input image located at img_input directory