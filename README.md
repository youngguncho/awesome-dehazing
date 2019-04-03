# Awesome Dehazing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
This repository is the collection of dehazing methods. Among various dehazing algorithms, we've selected the datasets provide pose and map information. This repository includes the list of dehazing (includes enhancement and restoration) papers, codes and datasets.

## Category
- [Dehazing methods](#dehazing-methods)
    - [Single image dehazing](#single-image-dehazing)
    - [Dehazing using multi-images](#dehazing-using-multi-images)
- [Specific topics](#specific-topics)
    - [Underwater](#underwater)
    - Night-time
    - Semantic
- [Dehazing datasets](#datasets)
    - Collection image of dehazing papers
    - [Open datasets](#open-datasets)


## Dehazing methods

### Single image dehazing
- Densely Connected Pyramid Dehazing Network [[Code](https://github.com/hezhangsprinter/DCPDN), [Paper](https://arxiv.org/abs/1803.08396)]
    - Zhang, He, and Vishal M. Patel. "Densely connected pyramid dehazing network." The IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2018.
- Multi-band Enhancement [[Code](https://github.com/irapkaist/multi-band-enhancement), [Paper](http://irap.kaist.ac.kr/index.php/Main/Publication?action=bibentry&bibfile=ref.bib&bibref=ycho-2018-ral)]
    - Cho, Younggun, Jinyong Jeong, and Ayoung Kim. "Model Assisted Multi-band Fusion for Single Image Enhancement and Applications to Robot Vision." IEEE Robotics and Automation Letters (2018).
  - Baseline for single image dehazing [[Code](https://github.com/nightldj/dehaze_release), [Paper](http://bmvc2018.org/contents/papers/0821.pdf)]
- Dehaze cGAN [[Code](https://github.com/hong-ye/dehaze-cGAN), [Paper](http://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Single_Image_Dehazing_CVPR_2018_paper.pdf)]
    - Li, Runde, et al. "Single Image Dehazing via Conditional Generative Adversarial Network." methods 3 (2018): 24.
- GFN Dehazing [[Code](https://github.com/rwenqi/GFN-dehazing), [Paper](https://arxiv.org/abs/1804.00213)]
    - Ren, Wenqi, et al. "Gated fusion network for single image dehazing." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018.
- AOD-net [[Code](https://github.com/Boyiliee/AOD-Net), [Paper](http://openaccess.thecvf.com/content_ICCV_2017/papers/Li_AOD-Net_All-In-One_Dehazing_ICCV_2017_paper.pdf)]
    - Li, Boyi, et al. "Aod-net: All-in-one dehazing network." Proceedings of the IEEE International Conference on Computer Vision. Vol. 1. No. 4. 2017.
- Non-local Image Dehazing [[Code](http://www.eng.tau.ac.il/~berman/NonLocalDehazing/), [Paper](http://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Berman_Non-Local_Image_Dehazing_CVPR_2016_paper.html)]
    - Berman, Dana, and Shai Avidan. "Non-local image dehazing." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.
- Dehazenet [[Code](https://github.com/caibolun/DehazeNet), [Paper](https://arxiv.org/abs/1601.07661)]
    - Cai, Bolun, et al. "Dehazenet: An end-to-end system for single image haze removal." IEEE Transactions on Image Processing 25.11 (2016): 5187-5198.
- Color Attenuation Prior (CAP) [[Code](http://web.siat.ac.cn/~qingsong/projects/single_image_dehazing/project.html), [Paper](http://web.siat.ac.cn/~qingsong/projects/single_image_dehazing/project.html)]
    - Zhu, Qingsong, Jiaming Mai, and Ling Shao. "A fast single image haze removal algorithm using color attenuation prior." IEEE Transactions on Image Processing 24.11 (2015): 3522-3533.
- DEFADE [[Code](http://live.ece.utexas.edu/research/fog/index.html), [Paper](https://ieeexplore.ieee.org/abstract/document/7159086)]
    - Choi, Lark Kwon, Jaehee You, and Alan Conrad Bovik. "Referenceless prediction of perceptual fog density and perceptual image defogging." IEEE Transactions on Image Processing 24.11 (2015): 3888-3901.
- Haze-relevant Features [[Code](https://github.com/zlinker/haze_2014), [Paper](http://www.cv-foundation.org/openaccess/content_cvpr_2014/html/Tang_Investigating_Haze-relevant_Features_2014_CVPR_paper.html)]
    - Tang, Ketan, Jianchao Yang, and Jue Wang. "Investigating haze-relevant features in a learning framework for image dehazing." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2014.
- Atm Light [[Code](http://www.cs.huji.ac.il/~raananf/projects/atm_light/), [Paper](http://www.cs.huji.ac.il/~raananf/projects/atm_light/)]
    - Sulami, Matan, et al. "Automatic recovery of the atmospheric light in hazy images." Computational Photography (ICCP), 2014 IEEE International Conference on. IEEE, 2014.
- Multi-scale Fusion [[Code (Third person)](https://kr.mathworks.com/matlabcentral/fileexchange/47147-image-dehazing-zip), [Paper](http://ieeexplore.ieee.org/abstract/document/6514885/)]
    - Ancuti, Codruta Orniana, and Cosmin Ancuti. "Single image dehazing by multi-scale fusion." IEEE Transactions on Image Processing 22.8 (2013): 3271-3282.
- Boudary Constraint and Contextual Regularization [[Code](http://www.escience.cn/people/menggaofeng/research.html), [Paper](http://www.escience.cn/system/file?fileId=65063)]
    - Meng, Gaofeng, et al. "Efficient image dehazing with boundary constraint and contextual regularization." Proceedings of the IEEE international conference on computer vision. 2013.
- Optimized Contrast Enhancement [[Code](http://mcl.korea.ac.kr/projects/dehazing/), [Paper](http://mcl.korea.ac.kr/~dotol1216/Publications/2013_JVCIR_JHKIM.pdf)]
    - Kim, Jin-Hwan, et al. "Optimized contrast enhancement for real-time image and video dehazing." Journal of Visual Communication and Image Representation 24.3 (2013): 410-425.
- Dehazing using Color-lines [[Code](http://www.cs.huji.ac.il/~raananf/projects/dehaze_cl/), [Paper](https://dl.acm.org/citation.cfm?id=2651362)]
    - Fattal, Raanan. "Dehazing using color-lines." ACM transactions on graphics (TOG) 34.1 (2014): 13.
- Dark Channel Prior [[Code (Third person)]( https://kr.mathworks.com/matlabcentral/fileexchange/46147-single-image-haze-removal-using-dark-channel-prior), [Paper](http://kaiminghe.com/cvpr09/index.html)]
    - He, Kaiming, Jian Sun, and Xiaoou Tang. "Single image haze removal using dark channel prior." IEEE transactions on pattern analysis and machine intelligence 33.12 (2011): 2341-2353.
- Fast Visibility Restoration [[Code](http://www.sciweavers.org/sourcecode/matlab-source-code-visibility-restoration-single-image), [Paper](http://ieeexplore.ieee.org/abstract/document/5459251/)]
    - Tarel, Jean-Philippe, and Nicolas Hautiere. "Fast visibility restoration from a single color or gray level image." Computer Vision, 2009 IEEE 12th International Conference on. IEEE, 2009.
- Single Image Dehazing [[Code](http://www.cs.huji.ac.il/~raananf/projects/defog/), [Paper]((http://www.cs.huji.ac.il/~raananf/projects/defog/))]
    - Fattal, Raanan. "Single image dehazing." ACM transactions on graphics (TOG) 27.3 (2008): 72.

### Dehazing using multi-images
- Simultaneous Defogging and Stereo Reconstruction [[Code](http://www.lizhuwen.com/pages/Stereo%20in%20Fog.html), [Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Li_Simultaneous_Video_Defogging_2015_CVPR_paper.pdf)]
    - Li, Zhuwen, et al. "Simultaneous video defogging and stereo reconstruction." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2015.
- Stereo Reconstruction and Contrast Restoration [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-37447-0_2)]
    - Caraffa, Laurent, and Jean-Philippe Tarel. "Stereo reconstruction and contrast restoration in daytime fog." Asian Conference on Computer Vision. Springer Berlin Heidelberg, 2012.

## Specific Topic
### Underwater
- UGAN [[Paper](https://www-users.cs.umn.edu/~islam034/papers/icra18_image.pdf)]
    - Fabbri, Cameron, Md Jahidul Islam, and Junaed Sattar. "Enhancing underwater imagery using generative adversarial networks." 2018 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2018.
- Underwater Haze-Line [[Code](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html), [Paper](http://csms.haifa.ac.il/profiles/tTreibitz/datasets/ambient_forwardlooking/index.html)]
    - Berman, Dana, et al. "Underwater Single Image Color Restoration Using Haze-Lines and a New Quantitative Dataset." arXiv preprint arXiv:1811.01343 (2018).
- Underwater Visiblity Enhancement [[Code](https://github.com/irapkaist/visibility_enhancement), [Paper](http://irap.kaist.ac.kr/publications/ycho-2017-icra.pdf)]
    - Cho, Younggun, and Ayoung Kim. "Visibility enhancement for underwater visual SLAM based on underwater light scattering model." Robotics and Automation (ICRA), 2017 IEEE International Conference on. IEEE, 2017.
- WaterGAN [[Code](https://github.com/ljlijie/WaterGAN-color-correction-net), [Paper](https://arxiv.org/abs/1702.07392)]
    - Li, Jie, et al. "WaterGAN: unsupervised generative network to enable real-time color correction of monocular underwater images." IEEE Robotics and Automation Letters 3.1 (2018): 387-394.
- Multi-scale Fusion [[Code (Third person)](https://kr.mathworks.com/matlabcentral/fileexchange/47147-image-dehazing-zip), [Paper](http://ieeexplore.ieee.org/abstract/document/6514885/)]
    - Ancuti, Codruta Orniana, and Cosmin Ancuti. "Single image dehazing by multi-scale fusion." IEEE Transactions on Image Processing 22.8 (2013): 3271-3282.

### Nighttime (Coming soon)

### Semantic (Coming soon)
- Semantic Single-Image Dehazing [[Paper](https://arxiv.org/abs/1804.05624)]
  - Cheng, Ziang, et al. "Semantic single-image dehazing." arXiv preprint arXiv:1804.05624 (2018).
- Semantic Video Dehazing [[Paper](http://lps3.ieeexplore.ieee.org.libra.kaist.ac.kr/stamp/stamp.jsp?tp=&arnumber=8492451)]
  - Ren, Wenqi, et al. "Deep video dehazing with semantic segmentation." IEEE Transactions on Image Processing 28.4 (2019): 1895-1908.

### Survey
- Benchmarking Single-Image Dehazing and Beyond [[Paper](https://ieeexplore.ieee.org/abstract/document/8451944)]
  - Li, Boyi, et al. "Benchmarking single-image dehazing and beyond." IEEE Transactions on Image Processing 28.1 (2019): 492-505.
- Haze Visibility Enhancement [[Paper](https://arxiv.org/pdf/1607.06235.pdf)]
  - Li, Yu, et al. "Haze visibility enhancement: A survey and quantitative benchmarking." Computer Vision and Image Understanding 165 (2017): 1-16.
-



## Datasets
### Collection of images (Coming soon)
- Collection of single image dehazing (Fattal, Berman, et al.) [[LINK]()]

### Open datasets
#### I-Haze / O-haze / D-Haze datasets
- I-Haze [[LINK](http://www.vision.ee.ethz.ch/ntire18/i-haze/)]
  - Ancuti, Cosmin, et al. "I-HAZE: a dehazing benchmark with real hazy and haze-free indoor images." International Conference on Advanced Concepts for Intelligent Vision Systems. Springer, Cham, 2018.
- O-Haze [[LINK](http://www.vision.ee.ethz.ch/ntire18/i-haze/))]
  - Ancuti, Codruta O., et al. "O-HAZE: a dehazing benchmark with real hazy and haze-free outdoor images." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2018.
- D-Haze (Link closed) [[LINK](http://www.meo.etc.upt.ro/AncutiProjectPages/D_Hazzy_ICIP2016/)]
  - Ancuti, Cosmin, Codruta O. Ancuti, and Christophe De Vleeschouwer. "D-HAZY: A dataset to evaluate quantitatively dehazing algorithms." 2016 IEEE International Conference on Image Processing (ICIP). IEEE, 2016.

#### Haze with Depth (+ Semantic)
- HazeRD (Depth) [[LINK](https://labsites.rochester.edu/gsharma/research/computer-vision/hazerd/)]
  - Zhang, Yanfu, Li Ding, and Gaurav Sharma. "Hazerd: an outdoor scene dataset and benchmark for single image dehazing." 2017 IEEE International Conference on Image Processing (ICIP). IEEE, 2017.
- Virtual Kitti Dataset (Depth + Semantic) [[LINK](http://www.europe.naverlabs.com/Research/Computer-Vision/Proxy-Virtual-Worlds)]
  - Gaidon, Adrien, et al. "Virtual worlds as proxy for multi-object tracking analysis." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.
- Semantic Dense Foggy Scene Understanding (Depth + Semantic) [[LINK](https://www.vision.ee.ethz.ch/~csakarid/Model_adaptation_SFSU_dense/)]
  - Christos Sakaridis, Dengxin Dai, Simon Hecker, and Luc Van Gool Model Adaptation with Synthetic and Real Data for Semantic Dense Foggy Scene Understanding European Conference on Computer Vision (ECCV), 2018

#### Underwater image datasets
- Turbid dataset [[LINK](http://amandaduarte.com.br/turbid/)]
  - Duarte, Amanda, et al. "A dataset to evaluate underwater image restoration methods." OCEANS 2016-Shanghai. IEEE, 2016.
