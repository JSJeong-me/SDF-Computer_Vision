# SDF-Computer_Vision

![guage-reader](https://user-images.githubusercontent.com/54794815/115826804-6ab75d80-a446-11eb-90f3-122d6aeedb49.jpg)


서울디지털재단 Youtube 강의 - Computer Vision


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

### Python(conda env) 환경 setting

###  (base) PS C:\Users\user> conda deactivate base
###  C:\Users\user> conda create --name sdf python=3.8.3
###  conda activate sdf
###  (sdf) pip install ipykernel
###  (sdf) python -m ipykernel install --user --name sdf --display-name "Python SDF"
###  (sdf) conda install -c conda-forge jupyterlab

    #
    # To activate this environment, use
    #
    #     $ conda activate sdf
    #
    # To deactivate an active environment, use
    #
    #     $ conda deactivate

### Remove sdf env
- (sdf) conda remove --name sdf --all
  
### OpenCV Python install
- (sdf) pip install opencv-python==4.4.0.46

### 또는
- (sdf) pip install -r requirements.txt
