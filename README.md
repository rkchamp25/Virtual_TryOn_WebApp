## Virtual Try On APP using PF-AFN

Install Anaconda or Miniconda to create a new/separate environment
```
conda create -n tryon python=3.6
source activate tryon or conda activate tryon
conda install pytorch=1.1.0 torchvision=0.3.0 cudatoolkit=9.0 -c pytorch
conda install cupy or pip install cupy==6.0.0
pip install opencv-python==4.5.1.48 fastapi "uvicorn[standard]" scipy
```