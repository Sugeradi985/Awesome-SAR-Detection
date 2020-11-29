# Awesome-SAR-Detection 🛳📡

- [Datasets](#datasets)
  - [LS SSD v1.0 OPEN](#ls-ssd-v10-open)
  - [SAR Ship Dataset](#sar-ship-dataset)
  - [SAR Ship Dataset Part1](#sar-ship-dataset-part1)
  - [SSDD](#ssdd)
  - [SSDD+](#ssdd-1)
  - [HRSID](#hrsid)

# Datasets
The datasets collected so far are all about ship detection. If there are other new data sets found, I will add them to this repository. If you find any links are unavailable, please contact me at: lijt55@mail2.sysu.edu.cn

## LS SSD v1.0 OPEN

#### [[GitHub Link]](https://github.com/TianwenZhang0825/LS-SSDD-v1.0-OPEN) 

#### [[Paper]](https://www.mdpi.com/2072-4292/12/18/2997): LS-SSDD-v1.0: A Deep Learning Dataset Dedicated to Small Ship Detection from Large-Scale Sentinel-1 SAR Images

This is a Large-Scale SAR Ship Detection Dataset-v1.0 (LS-SSDD-v1.0) from Sentinel-1, for small ship detection under large-scale backgrounds. LS-SSDD-v1.0 contains 15 large-scale SAR images whose ground truths are correctly labeled by SAR experts by drawing support from Automatic Identification System (AIS) and Google Earth. To facilitate network training, the large-scale images are directly cut into 9,000 sub-images without bells and whistles, providing convenience for subsequent detection result presentation in large-scale SAR images.

LS-SSDD-v1.0 is publicly available at:

Google Cloud: https://drive.google.com/file/d/1-fSKYsKr5wuYuXJE2CDX_Yfr4Ylwjfqm/view?usp=sharing

Baidu Cloud: https://pan.baidu.com/s/1VzqyQHIZL1uPaHmSnRLxPg (Extraction code: 2020)

```bibtex
@article{DBLP:journals/remotesensing/ZhangZKZSWPLSZK20,
  author    = {Tianwen Zhang and
               Xiaoling Zhang and
               Xiao Ke and
               Xu Zhan and
               Jun Shi and
               Shunjun Wei and
               Dece Pan and
               Jianwei Li and
               Hao Su and
               Yue Zhou and
               Durga Kumar},
  title     = {LS-SSDD-v1.0: {A} Deep Learning Dataset Dedicated to Small Ship Detection
               from Large-Scale Sentinel-1 {SAR} Images},
  journal   = {Remote. Sens.},
  volume    = {12},
  number    = {18},
  pages     = {2997},
  year      = {2020},
  url       = {https://doi.org/10.3390/rs12182997},
  doi       = {10.3390/rs12182997},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

## SAR Ship Dataset
#### [[GitHub]](https://github.com/CAESAR-Radi/SAR-Ship-Dataset)
#### [[Paper]](https://www.mdpi.com/2072-4292/11/7/765): A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds
This dataset labeled by SAR experts was created using 102 Chinese Gaofen-3 images and 108 Sentinel-1 images. It consists of 43,819 ship chips of 256 pixels in both range and azimuth. These ships mainly have distinct scales and backgrounds. It can be used to develop object detectors for multi-scale and small object detection. 
SAR-Ship-Dataset is publicly available at:
Baidu Cloud (from [issues](https://github.com/CAESAR-Radi/SAR-Ship-Dataset/issues/50)): https://pan.baidu.com/s/1PhSMkXVcuRM8M8xL15iBIQ

```bibtex
@article{DBLP:journals/remotesensing/WangWZDW19a,
  author    = {Yuanyuan Wang and
               Chao Wang and
               Hong Zhang and
               Yingbo Dong and
               Sisi Wei},
  title     = {A {SAR} Dataset of Ship Detection for Deep Learning under Complex
               Backgrounds},
  journal   = {Remote. Sens.},
  volume    = {11},
  number    = {7},
  pages     = {765},
  year      = {2019},
  url       = {https://doi.org/10.3390/rs11070765},
  doi       = {10.3390/rs11070765},
}
```
## SAR Ship Dataset Part1
Part of `SAR-Ship-Dataset`
#### [[GitHub]](https://github.com/ChrisYang/SAR-Ship-Dataset)
#### [[Paper]](https://www.mdpi.com/2072-4292/11/7/765): A SAR Dataset of Ship Detection for Deep Learning under Complex Backgrounds

## SSDD
#### [[知乎]](https://zhuanlan.zhihu.com/p/58404659)
#### [[Paper]](https://ieeexplore.ieee.org/document/8124934): Ship detection in SAR images based on an improved faster R-CNN

Baidu Cloud: https://pan.baidu.com/s/1E8ixqK5AVfXc98UgQmpqaw (Extraction code: trnt, Password: 12345qwert)

## SSDD+
#### [[知乎]](https://zhuanlan.zhihu.com/p/58404659)
#### [[Paper]](https://ieeexplore.ieee.org/document/8124934): Ship detection in SAR images based on an improved faster R-CNN
Baidu Cloud: https://pan.baidu.com/s/1jxOjbRqmmJfQnHHTieHSpA (Extraction code: f7zj)
Here only the `annotations` file is provided, and the images are the same with `SSDD Dataset`.

## HRSID
#### [[GitHub]](https://github.com/chaozhong2010/HRSID)
#### [[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9127939): HRSID: A High-Resolution SAR Images Dataset for Ship Detection and Instance Segmentation

High resolution sar images dataset (HRSID) is a data set for ship detection, semantic segmentation, and instance segmentation tasks in high-resolution SAR images. This dataset contains a total of 5604 high-resolution SAR images and 16951 ship instances. HRSID dataset draws on the construction process of the Microsoft Common Objects in Context (COCO) datasets, including SAR images with different resolutions, polarizations, sea conditions, sea areas, and coastal ports. This dataset is a benchmark for researchers to evaluate their approaches. For HRSID, the resolution of SAR images is as follows: 0.5m, 1 m, and 3 m.

HRSID dataset(JPG) can be downloaded from: 
Baidu cloud: https://pan.baidu.com/s/1z0-E3Lwdkg14feu1FwRf3g (Extraction code: bs64)
Google cloud: https://drive.google.com/open?id=1BZTU8Gyg20wqHXtBPFzRazn_lEdvhsbE

HRSID can be downloaded from Google Cloud: Compared to the latest released version of jpg format images of HRSID, we have added the annotations for inshore and offshore ships. Statistically, inshore scenes occupy the proportion of 18.4%, and offshore scenes occupy the proportion of 81.6%. It can be downloaded from URL https://drive.google.com/file/d/1NY3ovgc-woDlNoQdyqzRB3t9McOBH5Ms/view?usp=sharing

As full negative SAR images can provide the information of land or sea clutter, we have prepared 400 SAR images with pure background for testing the robustness of the trained model. It can be downloaded from the URL https://drive.google.com/file/d/1U0Sj1SHoq-2VjXXUKwpXae6rBI3YjyDP/view?usp=sharing

Here is the other version HRSID with png format images. It takes up much more storage space than the version of HRSID with jpg format images, while the high-fidelity SAR images are stored here. This version can be downloaded from the URL: https://drive.google.com/file/d/1xgXi8KC3MDWuu7Yp4n2J-LOPYLRszHAc/view?usp=sharing

HRSID can be downloaded from Baidu Cloud: The files can also be downloaded from URL:Baidu cloud. Extraction code: vxrs https://pan.baidu.com/s/1EitHYJ7tpGh0q9Qb3QA5SQ