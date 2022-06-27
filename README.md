# fps-grid
Converts molecular fingerprints to grids for image-based DL
This code is based on the [Griddify tool](https://github.com/ersilia-os/griddify) developed by Ersilia 

# Installation
1. Create a conda environment
2. Clone and install the griddify library from Ersilia's Repository
```
git clone https://github.com/ersilia-os/griddify.git
cd griddify
pip install -e .
```

# Example
In this example, provide a pre-trained grid generator based on ChEMBL29. The grid has been created using Rdkit ECPF-Counts with radius 3 and 1024 bits