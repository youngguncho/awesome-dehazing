# Awesome Dehazing
This repository is the collection of dehazing methods. Among various dehazing algorithms, we've selected the datasets provide pose and map information. This repository includes the list of dehazing (includes enhancement and restoration) papers, codes and datasets.

## Category
- Dehazing methods
    - Single Image
    - Learning-based
    - Known Depth
- Environments
    - General
    - Underwater
    - Night-time
- Dehazing datasets
    - Collection image of dehazing papers
    - Open datasets


## Dehazing methods

### Single image dehazing
- Densely Connected Pyramid Dehazing Network [[Code](https://github.com/hezhangsprinter/DCPDN), [Paper](https://arxiv.org/abs/1803.08396)]
    - Zhang, He, and Vishal M. Patel. "Densely connected pyramid dehazing network." The IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2018.
- Multi-band Enhancement [[Code](https://github.com/irapkaist/multi-band-enhancement), [Paper](http://irap.kaist.ac.kr/index.php/Main/Publication?action=bibentry&bibfile=ref.bib&bibref=ycho-2018-ral)]
    - Cho, Younggun, Jinyong Jeong, and Ayoung Kim. "Model Assisted Multi-band Fusion for Single Image Enhancement and Applications to Robot Vision." IEEE Robotics and Automation Letters (2018).
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
- Single Image Dehazing [[Code](http://www.cs.huji.ac.il/~raananf/projects/defog/), [Paper](http://www.cs.huji.ac.il/~raananf/projects/defog/)]
    - Fattal, Raanan. "Single image dehazing." ACM transactions on graphics (TOG) 27.3 (2008): 72.
