# RS-FID
This is a modified version of the [pytorch-fid](https://github.com/mseitzer/pytorch-fid) package, which is a PyTorch implementation of the Fréchet Inception Distance (FID) score used for evaluating the quality of RS images.

The original README is [here](Original_README.md).

## FID for Remote-Sensing Images
The inception model code is originally from [Txt2Img-MHN](https://github.com/YonghaoXu/Txt2Img-MHN/).

## Installation
```bash
git clone git@github.com:YanxingLiu/rs-fid.git
cd rs-fid
pip install -v -e .
```

## Usage
```bash
python -m pytorch_fid path/to/dataset1 path/to/dataset2
```
