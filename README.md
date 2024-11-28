# FGSCM-52
The dataset in the TGRS24 "Efficient Prompt Tuning of Large Vision-Language Model for Fine-Grained Ship Classification"

<p align="center">

  <h2 align="center"><strong>Scaling Efficient Masked Autoencoder Learning on Large Remote Sensing Dataset</strong></h2>

  <p align="center">
      Long Lan<sup>1</sup>&nbsp;&nbsp;&nbsp;
   Fengxiang Wang <sup>1,‡</sup>&nbsp;&nbsp;
    Xiangtao Zheng<sup>2</sup>&nbsp
    Zengmao Wang<sup>3</sup> &nbsp;&nbsp;
    Xinwang Liu<sup>1</sup>&nbsp;&nbsp;&nbsp;
    </br></br>
  <sup>1</sup> National University of Defense Technology&nbsp;&nbsp;&nbsp;
  <sup>2</sup>Fuzhou University&nbsp;&nbsp;
  <sup>3</sup>Wuhan University&nbsp;&nbsp;</br>
  </p>

## Intruduction
-  `FGSCM-52`: We contribute to the field by introducing a comprehensive dataset, FGSCM-52, significantly expanding existing datasets with more extensive data and detailed annotations for less common ship classes. </br>
- `Method`: We introduce a novel prompt tuning technique that employs a hierarchical, multi-granularity prompt design. Our approach integrates remote sensing ship priors through bias terms, learned from a small trainable network. This strategy enhances the model's generalization capabilities while improving its ability to discern intricate backgrounds and learn discriminative ship features. 


## Todo List
- [x] Initial release of FGSCM-52. 🚀
- [ ] Codes and configs for method. 



## Updates

- \[2024.11\] - The FGSCM-52 dataset have been released.



## Outline

- [FGSCM-52](#FGSCM-52)
- [Installation](#gear-installation)
- [Pretraining](#blue_car-Pretraining)
- [Downstream Tasks](#rocket-Results-on-downstream-tasks)
- [Citation](#citation)
- [License](#license)
- [Acknowledgements](#acknowledgements)


## FGSCM-52
 `RS-4M` dataset contains about 4 million high-quality remote sensing optical images, which is four times larger than previous representative remote sensing datasets.

### Examples of RS-4M
<img src="./Figures/FGSCM.png" width="700"> 

### Experiments on RS-4M

## SelectiveMAE

### :gear: Installation

For details related to installation, kindly refer to [INSTALL.md](docs/INSTALL.md).


###  :blue_car:  Pretraining

To learn more usage about the pretraining codes, kindly refer to [PRETRAIN.md](docs/GET_STARTED.md).


### :rocket: Results on downstream tasks


## License

This work is under the [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0), while some specific operations in this codebase might be with other licenses. 

## Acknowledgements
