# polarization-in-computer-vision
A collection of polarization-based models in computer vision. Main interest lies in scene understanding.


# [Table of Contents]()

* [Papers and Code](#Papers-and-Code)
* [Books](#Books)
* [Lecture Videos](#Lecture-Videos)
* [Datasets](#Datasets)
* [Tools](#Tools)
* [Research groups](#Research-groups)


## [Papers and Code]()

A curated set of papers along with code.


### [Polarization in 3D Computer Vision]()

* __Shape from Polarization for Complex Scenes in the Wild__, (2022), CVPR, [code](https://github.com/ChenyangLEI/sfp-wild). 
* __Polarimetric Helmholtz Stereopsis__, (2021), ICCV. 
* __Polarimetric Normal Stereo__, (2021), CVPR. 
* __Shape from Sky: Polarimetric Normal Recovery Under The Sky__, (2021), CVPR. 
* __Deep Polarization Imaging for 3D Shape and SVBRDF Acquisition__, (2021), CVPR. 
* __Polarimetric Monocular Dense Mapping Using Relative Deep Depth Prior__, (2021), RAL. 
* __P2D: a self-supervised method for depth estimation from polarimetry__, (2020), [paper](https://arxiv.org/pdf/2007.07567.pdf), **dataset**
* __Deep Shape from Polarization__, (2020), _Yunhao Ba, Alex Ross Gilbert, Franklin Wang, Jinfa Yang, Rui Chen, Yiqin Wang, Lei Yan, Boxin Shi, Achuta Kadambi_. [[pdf]](https://arxiv.org/abs/1903.10210) [[website]](https://visual.ee.ucla.edu/deepsfp.htm), **dataset**
* __Depth from a polarisation + RGB stereo pair__, (2019), _Zhu, Dizhong and Smith, William AP_. [[pdf]](https://arxiv.org/abs/1903.12061) [[code]](https://github.com/AmosZhu/CVPR2019) 
* __Mirror Surface Reconstruction Using Polarization Field__, (2019), ICIP
* __Polarimetric Relative Pose Estimation__, (2019), _Cui et al._
* __Depth from stereo polarization in specular scenes for urban robotics__, (2017)
* __Polarisation photometric stereo__, (2017)
* __Polarimetric three-view geometry__, (2018)
* __Polarimetric multi-view stereo__, (2017)
* __Shape and light directions from shading and polarization__, (2015)
* __Polarized 3d: High-quality depth sensing with polarization cues__, (2015)
* __Direct method for shape recovery from polarization and shading__, (2012)
* __Shape and refractive index recovery from single-view polarisation images__, (2010)
* __Shape estimation using polarization and shading from two views__, (2007)
* __What is the range of surface reconstructions from a gradient field__,  (2006)
* __Recovery of surface orientation from diffuse polarization__, (2006)
* __Polarization imaging applied to 3D reconstruction of specular metallic surfaces__, (2005)
* __Transparent surface modeling from a pair of polarization images__, (2004)
* __Polarization-based inverse rendering from a single view__, (2003)
* __Separating reflections and lighting using independent components analysis__, (1999)



### [Polarization in Image Enhancement]()

* __Multi-polarization fusion generative adversarial networks for clear underwater imaging__, (2022), underwater dataset
* __Polarized Reflection Removal with Perfect Alignment in the Wild__, (2020), _Chenyang Lei, Xuhua Huang, Mengdi Zhang, Qiong Yan, Wenxiu Sun, and Qifeng Chen_. [[pdf]](https://cqf.io/papers/Polarized_Reflection_Removal_CVPR2020.pdf) [[code]](https://github.com/ChenyangLEI/CVPR2020-Polarized-Reflection-Removal-with-Perfect-Alignment), CVPR. **dataset**
* __Reflection separation using a pair of unpolarized and polarized images__, (2019)
* __Image dehazing using polarization effects of objects and airlight__, (2014)
* __A physically-based approach to reflection separation: from physical modeling to constrained optimization__, (2013)
* __Clear underwater vision__, (2004)

### [Polarization in Image Segmentation and Detection]()
* __Deep Polarization Cues for Transparent Object Segmentation__, (2020),  [Link](https://kalraa.github.io/)
* __HDR Reconstruction Based on the Polarization Camera__, (2020)
* __A New Multimodal RGB and Polarimetric Image Dataset for Road Scenes Analysis__, (2020), [dataset](http://pagesperso.litislab.fr/rblin/databases/)
* __Outdoor Scenes Pixel-wise Semantic Segmentation using Polarimetry and Fully Convolutional Network__, (2019), **datast**
* __Road scenes analysis in adverse weather conditions bypolarization-encoded images and adapted deep learning__, (2019)
* __Adapted learning for polarization-based car detection__, (2019)


### [Polarization in Other Tasks]()

* __Polarized Optical-Flow Gyroscope__, (2020), ECCV
* __Monochrome and color polarization demosaicking using edge-aware residual interpolation__, (2020)
* __Face Anti-Spoofing by Learning Polarization Cues in a Real-World Scenario__, (2020)
* __Attitude Estimation from Polarimetric Cameras__, (2018)
* __Survey of demosaicking methods for polarization filter array images__, (2018)
* __Simultaneous acquisition of polarimetric SVBRDF and normals.__, (2018)
* __Polarization imaging reflectometry in the wild__, (2017)
* __Enhanced material classification using turbulence-degraded polarimetric imagery__, (2010)
* __Polarization phase-based method for material classification in computer vision__, (1998)


## [Books]()

* [Field Guide to Polarization](https://www.spiedigitallibrary.org/ebooks/FG/Field-Guide-to-Polarization/eISBN-9780819478207/10.1117/3.626141)
* [Computational Imaging Book 2022](https://imagingtext.github.io/)  (Section 7  Polarimetric Imaging)


## Lecture Videos 
* __Sony polarsens__[[Introduction]](https://www.youtube.com/watch?v=cvT3t66dbMk)[[Application]](https://www.youtube.com/watch?v=Stsfnwdt09Y)

## Datasets

* __PolarLITIS dataset__[[Link]](https://pagesperso.litislab.fr/rblin/databases/)\
  __Format__: (I0, I45, I135), (S0, S1, S2),(S0, AOP, DOP)　　　　 __Task__: Object detection　　　　 __Scene__: road scenes \
  __Num.__:2K+ Polar-mono/RGB　　　 __pCamera__: Polarcam 4D　　　 __Other__:  adverse weather conditions( foggy, sunny and cloudy)
* __PolarBot dataset__[[Link]](http://vibot.cnrs.fr/polabot.html)\
  __Format__: HSV 　　　　 __Task__: semantic segmentation　　　　 __Scene__: outdoor road scenes \
  __Num.__: 200+ Polar/BGR　　　 __pCamera__: Polarcam　　　 __Other__:  with segmentation GT, data augmentation
* __Zhejiang university pRGB dataset___[[Link]](http://www.wangkaiwei.org/download.html)\
  __Format__: stereo polarized RGB 　　　 __Task__: polarization information prediction　　　 __Scene__: road scenes \
  __Num.__: 9736 Polar/RGB　　　 __pCamera__: Polarcam　　　 __Other__:  Polarization difference GT,  wearable robots
* __deepSfP dataset__[[Link]](https://visual.ee.ucla.edu/deepsfp.htm)\
  __Format__: 4ch_polar/object GT/normal GT 　　　 __Task__: 3D Reconstruction　　　 __Scene__: objects \
  __Num.__: 300 images　　　 __pCamera__: Lucid Vision Phoenix　　　 __Other__:  33 scanned objects, indoor/outdoor sunny/outdoor cloudy
* __SPW dataset__[[Link]](https://github.com/ChenyangLEI/sfp-wild)\
  __Format__: polar-mono/normal GT 　　　 __Task__: 3D Reconstruction　　　 __Scene__: real-world \
  __Num.__: 522 images　　　 __pCamera__: Lucid Vision Phoenix　　　 __Other__:   100 different scenes, near-field depth
* __synthetic foggy dataset__[[Link]](https://github.com/fourson/Learning-to-dehaze-with-polarization)\
  __Task__: image dehazing　　　　 __Scene__: synthetic/outdoor 　　　__Other__:   based on Foggy Cityscapes dataset

## Tools
* __A Polarizing Filter Function for Real-Time Rendering__[[pdf]](https://jcgt.org/published/0010/02/03/)[[demo]](https://www.youtube.com/watch?v=3nMkQh3mKsI)

## Research groups
* __Camera Intelligence Lab @PKU__[[Link]](https://ci.idm.pku.edu.cn/Publication.htm)
* __Visual Intelligence Lab @HKUST__[[Link]](https://ece.hkust.edu.hk/research/areas)
* __ImViA & LITIS Lab__   French ICUB project[[Link]](https://anr.fr/Project-ANR-17-CE22-0011)　VIPeR project[[Link]](https://anr.fr/Project-ANR-15-CE22-0009)
* __Kaiwei Wang's Group @ZJU__[[Link]](http://www.wangkaiwei.org/project.html)
* __Visual Machines Group @UCLA__[[Link]](https://visual.ee.ucla.edu/)
