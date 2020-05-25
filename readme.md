
Riemannian covariance descriptors(RieCovDs) via covariance computation on the manifold of Gaussians for image set coding.  
Written by Kai-Xuan Chen (e-mail: kaixuan_chen_jsh@163.com)  


The ETH-80 dataset is needed to be downloaded(https://github.com/Kai-Xuan/ETH-80/),  
and put 8 filefolders(visual image sets from 8 different categories) into filefolder '.\ETH-80\'.  
Please run 'read_ETH.m' to generate RieCovDs. Then run 'run_ETH_NNMethods.m' and 'run_ETH_DisMethods.m' for image set classification.  


Please cite the following paper (more theoretical and technical details) if your are using this code:
```
@article{chen2020riecovds,
  title={Covariance Descriptors on a Gaussian Manifold and their Application to Image Set Classification},
  author={Chen, Kai-Xuan and Ren, Jie-Yi and Wu, Xiao-Jun and Kittler, Josef},
  journal={Pattern Recognition},
  year={2020},
  publisher={Elsevier}
}
```


For more experiment, you can test on Virus dataset (https://github.com/Kai-Xuan/Virus/) 


