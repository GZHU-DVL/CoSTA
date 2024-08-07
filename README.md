# StarVQAplus
StarVQA+: Co-training Space-Time Attention for Video Quality Assessment
(The code is constantly being updated)
#  Installation

First, create a conda virtual environment and activate it:

```
conda create -n StarVQAplus python=3.7 -y
source activate StarVQAplus
```
Then, install the following packages:

- fvcore: pip install 'git+https://github.com/facebookresearch/fvcore'
- simplejson: pip install simplejson
- einops: pip install einops
- timm: pip install timm
- PyAV: conda install av -c conda-forge
- psutil: pip install psutil
- scikit-learn: pip install scikit-learn
- OpenCV: pip install opencv-python
- tensorboard: pip install tensorboard

Clone this repo.

```
git clone https://github.com/GZHU-DVL/StarVQAplus.git
cd StarVQA
python setup.py build develop
```

Please replace the data path with your local path 
# Pretrain model
Space-attention weights after training on ImageNet-1k.

[**vit_small_patch16_224**](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-weights/vit_small_p16_224-15ec54c9.pth)

[**vit_base_patch16_224**](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_base_p16_224-80ecf9dd.pth)

[**vit_large_patch16_224**](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_large_p16_224-4ee7a4dc.pth)

Space-attention weights after training on ImageNet-21k.

[**vit_base_patch16_224_in21k**](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_base_patch16_224_in21k-e5005f0a.pth)

[**vit_large_patch16_224_in21k**](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_large_patch16_224_in21k-606da67d.pth)

Space-time-attention weights after training on VQA datasets.

[**checkpoint-baidu**](https://pan.baidu.com/s/1ZVQWXOI12sKFjSA1sjdORw?pwd=knmb) 提取码:knmb
# Acknowledgements
StarVQAplus is built on top of [**TimeSformer**](https://github.com/facebookresearch/TimeSformer) and pytorch-image-models by [**Ross Wightman**](https://github.com/rwightman). We thank the authors for releasing their code. If you use our model, please consider citing these works as well:
```
@inproceedings{gberta_2021_ICML,
    author  = {Gedas Bertasius and Heng Wang and Lorenzo Torresani},
    title = {Is Space-Time Attention All You Need for Video Understanding?},
    booktitle   = {Proceedings of the International Conference on Machine Learning (ICML)}, 
    month = {July},
    year = {2021}
}
```
```
@misc{rw2019timm,
  author = {Ross Wightman},
  title = {PyTorch Image Models},
  year = {2019},
  publisher = {GitHub},
  journal = {GitHub repository},
  doi = {10.5281/zenodo.4414861},
  howpublished = {\url{https://github.com/rwightman/pytorch-image-models}}
}
```

