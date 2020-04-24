### About

Corresponding code to the paper "Sparse Semidefinite Programs with Guaranteed 
Near-Linear Time Complexity via Dualized Clique Tree Conversion" by 
Richard Y. Zhang and Javad Lavaei, at https://arxiv.org/abs/1710.03475

This code was also used in the paper "Large-Scale Traffic 
Signal Offset Optimization" by Yi Ouyang, Richard Y. Zhang, Javad Lavaei, 
and Pravin Vairaya, at https://arxiv.org/abs/1911.08368

### Prerequisites

You will need an SDP solver to solve the SDP generated by the code. The code 
works natively with [SeDuMi](https://github.com/sqlp/sedumi), though users are encouraged to install [MOSEK](https://www.mosek.com/) as it is _significantly_ faster. The 
translation code between SeDuMi and MOSEK was taken from [YALMIP](https://yalmip.github.io/); please remember to [cite Johan](https://yalmip.github.io/reference/lofberg2004/) if you use this module. 

### Licence

This code is provided under the BSD 2-Clause, Copyright 2020 to [Richard Y. Zhang](http://ryz.nz).

### Citation

The journal version is currently under minor revisions and should be published soon. 
```
@article{zhang2017sparse,
  title={Sparse semidefinite programs with guaranteed near-linear time complexity via dualized clique tree conversion},
  author={Zhang, Richard Y and Lavaei, Javad},
  journal={arXiv preprint arXiv:1710.03475},
  year={2017}
}
```

An earlier, conference version of this paper was published at IEEE CDC 2018.
```
@inproceedings{zhang2018sparse,
  title={Sparse semidefinite programs with near-linear time complexity},
  author={Zhang, Richard Y and Lavaei, Javad},
  booktitle={IEEE Conference on Decision and Control (CDC) 2018},
  pages={1624--1631},
  year={2018},
  organization={IEEE}
}
```