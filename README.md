# CGDC


## Run the code
This repository primarily contains a demonstration of enhancing a graph convolutional network (GCN) with curvanture graph diffusion convolution (CGDC) in the notebook `gdc_demo.py`.

## Requirements
The repository uses these packages:

```
pyyaml
tqdm>=4.36
numpy
scipy
seaborn
pytorch>=1.3
pytorch_geometric
```

## PyTorch Geometric

CGDC is also implemented as a transformation (preprocessing step) in [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/modules/transforms.html#torch_geometric.transforms.GDC). So you can just apply it to your own dataset and see how your existing PyG model improves!


## Cite
Please cite our paper if you use the model or this code in your own work

