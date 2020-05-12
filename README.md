# CGDL-for-Open-Set-Recognition
Code for CVPR2020 paper: Conditional Gaussian Distribution Learning for Open Set Recognition: https://arxiv.org/abs/2003.08823

python 3.6, pytorch 1.4, opencv-python, rpy2


For training, run lvae_train.py file;
For testing, run qmv.py file; you will need the mvtnorm package from R. You can install it as follows:

```
wget https://cran.r-project.org/src/contrib/mvtnorm_1.1-0.tar.gz
Rscript -e 'install.packages("./mvtnorm_1.1-0.tar.gz", repos=NULL, type = "source")'
```

