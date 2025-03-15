# 安装教程

1. 创建 `conda` 环境
```bash
mamba create -n chem_motif_identifier python=3.9
mamba activate chem_motif_identifier
```
2. 安装`pytorch`等

参考官方文档 

[`pytorch`](https://pytorch.org/get-started/locally/)

 [`PyTorch Geometric`](https://pytorch-geometric.readthedocs.io/en/latest/)

注意 二者版本对应

3. 安装`chemicalmotifidentifier`
```bash
pip install git+https://github.com/9527567/ChemicalMotifIdentifier.git
```