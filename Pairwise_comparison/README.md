# Pairwise comparision

Official github of the paper "Monocular Depth Estimation of Old Photos via Collaboration of Monocular and Stereo Networks", IEEE Access, Ju Ho Kim, [Kwang-Lim Ko](https://github.com/kklim1323), Le Thanh Ha, and Seung-Won Jung [[PAPER](https://ieeexplore.ieee.org/document/10034739)]


# Requirements

This code is implemented with Python 3.6 (Anaconda)

```
open3d==0.12.0
numpy
screeninfo
opencv-python
```


# Old Photo Dataset

The dataset was crawled old photos from onlie library.
[Library of congress](https://www.loc.gov/pictures/)

[Old Photo Restoration](https://github.com/microsoft/Bringing-Old-Photos-Back-to-Life) was used for dataset. 


# Folder Description

```
old_depth     : depth result images
old_xyz       : xyzrgb.txt files
original_old  : original(before restoration) images
restored_old  : restored(after restoration) images
```


# GUI example

<img src="https://github.com/rmawngh/Old-Photo-3D/blob/main/Pairwise_comparison/gui_example.png">





## Citation
```
@ARTICLE{10034739,
  author={Kim, Ju Ho and Ko, Kwang-Lim and Le Ha, Thanh and Jung, Seung-Won},
  journal={IEEE Access}, 
  title={Monocular Depth Estimation of Old Photos via Collaboration of Monocular and Stereo Networks}, 
  year={2023},
  volume={11},
  number={},
  pages={11675-11684},
  doi={10.1109/ACCESS.2023.3241348}}
```

