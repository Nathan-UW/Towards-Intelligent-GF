# Towards-Intelligent-GF
**Towards Intelligent Ground Filtering of Large-Scale Topographic Point Clouds: A Comprehensive Survey** 

Nannan Qin, Weikai Tan, Haiyan Guan, Lanying Wang, Lingfei Ma, Pengjie Tao, Sarah Fatholahi, Xiangyun Hu∗, Jonathan Li∗

**[[Paper](https://www.sciencedirect.com/science/article/pii/S1569843223003904)]**

# Abstract
With the fast development of 3D data acquisition techniques, topographic point clouds have become easier to acquire and have promoted many geospatial applications. Ground filtering (GF), as one of the most fundamental and challenging tasks for the post-processing of large-scale topographic point clouds, has been extensively studied but has yet to be well solved. To reveal future superior solutions, a comprehensive investigation of up-to-date GF studies is essential. However, existing GF surveys are scarce and fail to capture the latest progress and advancements. To this end, this paper not only presents a comprehensive review of up-to-date and advanced GF methods, but also conducts systematic comparative analyses of existing experimental results on public GF benchmark datasets. Moreover, this survey compiles the most recent publicly available resources that can be leveraged for the GF research, including pertinent datasets, metrics, and a range of open-source tools. Finally, the remaining challenges and promising research directions of GF, as well as implications for large-scale 3D geospatial understanding, are discussed in-depth. It is expected that this survey can simultaneously serve as a position paper and tutorial to those interested in GF.

## Publication Trends

![Image](Imgs/Typical_Publications.png)

## Public Datasets
ISPRS-Filtertest: https://www.itc.nl/isprs/wgIII-3/filtertest<br />
OpenGF: https://github.com/Nathan-UW/OpenGF<br />
Forested environment: https://3decology.org/2023/06/21/benchmark-dataset-for-airborne-lidar-scanning-data-filtering-in-forested-environments-2/ <br />

## Open-source Tools
### Free Software
ALDPAT: http://LiDAR.ihrc.fiu.edu/LiDARtool.html <br />
PCL: https://pointclouds.org/downloads/<br />
PDAL: https://pdal.io<br />
FUSION/LDV: http://forsys.sefs.uw.edu/fusion/fusionlatest.html<br />
MCC-LiDAR: http://sourceforge.net/projects/mccLiDAR/develop<br />
BCAL LiDAR Tools: http://bcal.boisestate.edu/tools/LiDAR/<br />
LASTools: http://www.cs.unc.edu/isenburg/lastools/<br />
CloudCompare: https://www.cloudcompare.org<br />

### Public DL Models
VGG: https://github.com/machrisaa/tensorflow-vgg<br />
FCN: https://github.com/shelhamer/fcn.berkeleyvision.org<br />
PointNet/PointNet++: https://github.com/intel-isl/Open3D-PointNet2-Semantic3D<br />
MinkUNet: https://github.com/NVIDIA/MinkowskiEngine<br />
DGCNN: https://github.com/AnTao97/dgcnn.pytorch<br />
KPConv: https://github.com/HuguesTHOMAS/KPConv<br />
RandLA-Net: https://github.com/QingyongHu/RandLA-Net<br />
SCF-Net: https://github.com/leofansq/SCF-Net<br />

## Citation

If it is helpful for your work, please consider citing our paper:

    @inproceedings{qin2023towardsIGF,
        title={Towards Intelligent Ground Filtering of Large-Scale Topographic Point Clouds: A Comprehensive Survey},
        author={Qin, Nannan and Tan, Weikai and Guan, Haiyan and Wang, Lanying  and Ma, Lingfei and Tao, Pengjie and Fatholahi, Sarah and Hu, Xiangyun and Li, Jonathan},
        journal={Int. J. Appl. Earth Obs. Geoinf.},
        year={2023}
        volume = {125},
        pages = {103566},
        doi = {https://doi.org/10.1016/j.jag.2023.103566}
    }
