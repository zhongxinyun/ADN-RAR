#  ADN-RAR: Adaptive Dictionary Network with Joint Tri-Domain Optimization for PCCT Ring Artifact Reduction

<h4 align="center">Xinyun Zhong<sup>1,</sup>, Qianjin Feng<sup>1,2</sup>, Yikun Zhang<sup>1</sup>, Xu Ji<sup>1,&dagger;</sup>, Yang Chen<sup>1,&dagger;</sup></center>
<h4 align="center"><sup>1</sup>Southeast University,</sup></center>
<h4 align="center"><sup>2</sup>Southern Medical University</sup></center>
<h4 align="center"><sup>&dagger;</sup>Corresponding Authors</center></center>

### Introduction
This repository represents the official implementation of our paper titled **ADN-RAR: Adaptive Dictionary Network with Joint Tri-Domain Optimization for PCCT Ring Artifact Reduction**. If you find this repo useful, please give it a star ⭐ and consider citing our paper in your research after publishing. Thank you.

We present ADN-RAR, a novel framework for PCCT Ring Artifact Reduction.

- **Tri-domain joint optimization framework**: explicitly models the ring artifact component in the artifact domain while simultaneously enforcing artifact suppression in both the Cartesian and Polar image domains.
- **Adaptive convolutional dictionary**: The dictionary provides a flexible and interpretable representation of ring patterns, enabling more effective suppression of artifact structures.
- **Dynamic hyper-parameter generator**: adaptively regulates the update step size in each iteration according to residual artifact intensity. 


### Results

**Simulate Dataset**

![simulate_rat_dataset](fig/simulate_rat_dataset.jpg)

**PCCT Real Dataset**

![simulate_rat_dataset](fig/simulate_rat_dataset.jpg)


## 📢 News
**2026-01-20:** Our paper has been submitted to IEEE Transactions on Image Processing (TIP) for peer review. Code and pretrained Models will be released after accept. :rocket:<br>

### 📦 Repository

Clone the repository (requires git):

```bash
git clone https://github.com/zhongxinyun/ADN-RAR.git
cd ADN-RAR
```
