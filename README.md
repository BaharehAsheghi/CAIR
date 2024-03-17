# CAIR
A Comprehensive Review on Content-Aware Image Retargeting: From Classical to State-of-the-art Methods (2022) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0165168422000433)]
 
[Content-aware image retargeting methods ](#headers1) 
* [Discrete methods](#headers11)  
   * [Content-aware cropping methods](#headers111)  
   * [Seam-carving-based methods](#headers112)  
   * [Shift-map method](#headers113)  
* [Continuous methods](#headers12)  
   * [Content-aware scaling methods](#headers121)  
   * [Warping-based methods](#headers122)
     * [Region-based methods](#headers1221)
     * [Pixel-based methods](#headers1222)
     * [Mesh-based methods](#headers1223)
       * [Vertex-based methods](#headers12231)
       * [Axis-aligned-based methods](#headers12232)
       * [Quad-edge-based method ](#headers12233)
* [Multi-operator methods](#headers13)
* [Deep learning-based methods](#headers14)

[Image retargeting quality assessment methods](#headers2)
* [Subjective RIQA methods](#headers21)
* [Objective RIQA methods](#headers22)

[Datasets](#headers3)
* [RetargetMe](#headers31)
* [CUHK](#headers32)
* [NRID](#headers33)
* [MSRA-1000](#headers34)
* [SED-100](#headers35)
  
## Content-aware image retargeting methods <a name="headers1">
### Discrete methods <a name="headers11">
#### Content-aware cropping methods <a name="headers111">
##### * A visual attention model for adapting images on small displays (2003) [[PDF](https://link.springer.com/article/10.1007/s00530-003-0105-4)]
##### * Auto cropping for digital photographs (2005) [[PDF](https://ieeexplore.ieee.org/abstract/document/1521454)]
##### * Self-adaptive image cropping for small displays (2007) [[PDF](https://ieeexplore.ieee.org/abstract/document/4429261)]
##### * Learning based thumbnail cropping (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/5202557)]
##### * Sensation-based photo cropping (2009) [[PDF](https://dl.acm.org/doi/abs/10.1145/1631272.1631384)]
##### * Combining multiple image features to guide automatic portrait cropping for rendering different aspect ratios (2010) [[PDF](https://ieeexplore.ieee.org/document/5714531)]
##### * Saliency density maximization for efficient visual objects discovery (2011) [[PDF](https://ieeexplore.ieee.org/abstract/document/5756228)]
#### Seam-carving-based methods <a name="headers112">
##### * Seam carving for content-aware image resizing (2007) [[PDF](https://dl.acm.org/doi/abs/10.1145/3596711.3596776)]
##### * Improved seam carving for video retargeting (2008) [[PDF](https://dl.acm.org/doi/abs/10.1145/1360612.1360615)]
##### * Saliency detection for content-aware image resizing (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/5413815)]
##### * Depth-aware image seam carving (2013) [[PDF](https://ieeexplore.ieee.org/abstract/document/6565369)]
##### * Saliency-based selection of gradient vector flow paths for content aware image resizing (2014) [[PDF](https://ieeexplore.ieee.org/abstract/document/6775267)]
##### * High quality image resizing (2014) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0925231213009545)]
##### * Learning to resize image (2014) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0925231213009521)]
##### * NIF-based seam carving for image resizing (2015) [[PDF](https://link.springer.com/article/10.1007/s00530-014-0425-6)]
##### * Image retargeting with a 3D saliency model (2015) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0165168414005039)]
##### * Improved seam carving combining with 3D saliency for image retargeting (2015) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0925231214013769)]
##### * Optimizing seam carving on multi-GPU systems for real-time content-aware image resizing (2015) [[PDF](https://link.springer.com/article/10.1007/s11227-015-1446-4)]
##### * Sparse seam-carving for structure preserving image retargeting (2016) [[PDF](https://link.springer.com/article/10.1007/s11265-015-1084-3)]
##### * Content-aware image resizing: An improved and shadow-preserving seam carving method (2019) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0165168418303244)]
##### * Reflection symmetry aware image retargeting (2019) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0167865519301205)]
##### * Distortion-aware image retargeting based on continuous seam carving model (2020) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0165168419302889)]
##### * Structure preservation of image using an efficient content-aware image retargeting technique (2021) [[PDF](https://link.springer.com/article/10.1007/s11760-020-01736-x)]
#### Shift-map method <a name="headers113">
##### * Shift-map image editing (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/5459159)]
### Continuous methods <a name="headers12">
#### Content-aware scaling methods <a name="headers121">
##### * A novel video image scaling algorithm based on morphological edge interpolation (2008) [[PDF](https://ieeexplore.ieee.org/abstract/document/4590378)]
##### * An improved edge-adaptive image scaling algorithm (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/5351551)]
##### * Patchwise scaling method for content-aware image resizing (2012) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S0165168411004038)]
##### * Stretchability-aware block scaling for image retargeting (2013) [[PDF](https://www.sciencedirect.com/science/article/pii/S1047320313000436)]
#### Warping-based methods <a name="headers122">
##### Region-based methods <a name="headers1221">
##### * Automatic image retargeting with fisheye-view warping (2005) [[PDF](https://dl.acm.org/doi/abs/10.1145/1095034.1095061)]
##### * Non-homogeneous content-driven video-retargeting (2007) [[PDF](https://ieeexplore.ieee.org/abstract/document/4409010)]
##### * Constrained sampling for image retargeting (2008) [[PDF](https://ieeexplore.ieee.org/abstract/document/4607705)]
##### * Fast structure-preserving image retargeting (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/4959767)]
##### * Adaptive image and video retargeting technique based on Fourier analysis (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/5206666)]
##### * Image retargeting with multifocus fisheye transformation (2013) [[PDF](https://link.springer.com/article/10.1007/s00371-012-0744-6)]
##### Pixel-based methods <a name="headers1222">
##### * Image retargeting based on global energy optimization (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/5202520)]
##### * Image and video retargetting by darting (2009) [[PDF](https://link.springer.com/chapter/10.1007/978-3-642-02611-9_4)]
##### * Image and video retargeting using adaptive scaling function (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/7077652)]
##### Mesh-based methods <a name="headers1223">
###### Vertex-based methods <a name="headers12231">
##### * Feature-aware texturing (2006) [[PDF](https://diglib.eg.org/bitstream/handle/10.2312/EGWR.EGSR06.297-303/297-303.pdf?sequence=1&isAllowed=y)]
##### * Optimized scale-and-stretch for image resizing (2008) [[PDF](https://dl.acm.org/doi/abs/10.1145/1457515.1409071)]
##### * A shape-preserving approach to image resizing (2009) [[PDF](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2009.01568.x)]
##### * Image retargeting using mesh parametrization (2009) [[PDF](https://ieeexplore.ieee.org/abstract/document/4907044)]
##### * Nonhomogeneous scaling optimization for realtime image resizing (2010) [[PDF](https://link.springer.com/article/10.1007/s00371-010-0472-8)]
##### * Image resizing via non-homogeneous warping (2012) [[PDF](https://link.springer.com/article/10.1007/s11042-010-0613-0)]
##### * Patch-based image warping for content-aware retargeting (2013) [[PDF](https://ieeexplore.ieee.org/abstract/document/6357312)]
##### * Dynamic distortion maps for image retargeting (2013) [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1047320312001654)]
##### * Image retargeting via adaptive scaling with geometry preservation (2014) [[PDF](https://ieeexplore.ieee.org/abstract/document/6720205)]
###### Axis-aligned-based methods <a name="headers12232">
##### * Robust image retargeting via axis-aligned deformation (2012) [[PDF](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2012.03001.x)]
##### * Image retargeting for preserving robust local feature: Application to mobile visual search (2015) [[PDF](https://ieeexplore.ieee.org/abstract/document/7328742)]
##### * A structure-aware axis-aligned grid deformation approach for robust image retargeting (2018) [[PDF](https://link.springer.com/article/10.1007/s11042-017-4674-1)]
###### Quad-edge-based method <a name="headers12233">
##### * A structure-aware axis-aligned grid deformation approach for robust image retargeting (2018) [[PDF](https://link.springer.com/article/10.1007/s11042-017-4674-1)]

### Multi-operator methods <a name="headers13">
### Deep learning-based methods <a name="headers14">
## Image retargeting quality assessment methods <a name="headers2">
### Subjective RIQA methods <a name="headers21">
### Objective RIQA methods <a name="headers22">
## Datasets <a name="headers3">
### RetargetMe <a name="headers31">
### CUHK <a name="headers32">
### NRID <a name="headers33">
### MSRA-1000 <a name="headers34">
### SED-100 <a name="headers35">
