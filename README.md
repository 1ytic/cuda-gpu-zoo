# Properties of the CUDA devices

The following code demonstrates how to get device properties from a Jupyter notebook, for example, from [kaggle](https://www.kaggle.com/kernels) or [colab](https://colab.research.google.com/notebooks/welcome.ipynb).

```
!git clone https://github.com/NVIDIA/cuda-samples

import os
os.chdir('cuda-samples/Samples/deviceQuery')

!make

!./deviceQuery
```
