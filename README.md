# The-State-of-the-Art-in-HDR-Deghosting

Collection of classical and popular multi-exposure image fusion works.
Most of works have codes available. 

![overview](https://github.com/JimmyChame/The-State-of-the-Art-in-HDR-Deghosting/blob/master/overview.png)

## Method
### Multi-exposure images fusion
##### Recovering High Dynamic Range Radiance Maps from Photographs (PE Debevec, J Malik. SIGGRAPH 1997) [[web]](https://www.pauldebevec.com/Research/HDR/)
##### Exposure Fusion (T Mertens, J Kautz, F Van Reeth. Pacific Graphics 2007) [[web]](https://mericam.github.io/exposure_fusion/index.html)

### Classical deghost methods
##### Artifact-free High Dynamic Range Imaging (O Gallo, N Gelfandz, et al. ICCP 2009) [[web]](http://alumni.soe.ucsc.edu/~orazio/deghost.html)
##### Motion-Blur-Free Exposure Fusion (M Tico, N Gelfand, K Pulli. ICIP 2010) [[paper]](https://people.csail.mit.edu/kapu/papers/tico_icip2010.pdf)

##### Ghost-Free High Dynamic Range Imaging (YS Heo, KM Lee, et al. ACCV 2010) [[web]](https://cv.snu.ac.kr/index.php/publication-international/)
##### Super High Dynamic Range Imaging (T Hayami, M Tanaka, et al. ICPR 2014) [[web]](http://www.ok.sc.e.titech.ac.jp/res/SHDR/SHDR.html)
##### Robust Multi-Exposure Image Fusion A Structural Patch Decomposition Approach (K Ma, H Li, et al. TIP 2017) [[web]](https://ece.uwaterloo.ca/~k29ma/)
##### Fast Multi-Scale Structural Patch Decomposition for Multi-Exposure Image Fusion (H Li, K Ma, et al. TIP 2020) [[web]](https://github.com/xiaohuiben/fmmef-TIP-2020)

### Optical-flow-based
##### Freehand HDR Imaging of Moving Scenes with Simultaneous Resolution Enhancement (H Zimmer, A Bruhn, J Weickert. EUROGRAPHICS 2011) [[web]](https://www.mia.uni-saarland.de/Research/SR-HDR/index.shtml)


### PatchMatch-Based
##### Robust Patch-Based HDR Reconstruction of Dynamic Scenes (P Sen, NK Kalantari, et al. SIGGRAPH Asia 2012) [[web]](http://cvc.ucsb.edu/graphics/Papers/Sen2012_PatchHDR/)
##### HDR Deghosting How to deal with Saturation (J Hu, O Gallo, et al. CVPR 2013) [[web]](http://www.cs.duke.edu/~junhu/CVPR2013/)
##### Hybrid Patching for a Sequence of Differently Exposed Images With Moving Objects (J Zheng, Z Li, et al. TIP 2013) [[paper]](https://ieeexplore.ieee.org/document/6607144)

### Rank Minimization
##### Ghost-Free High Dynamic Range Imaging via Rank Minimization (C Lee, Y Li, et al. SPL 2014) [[web]](http://cilab.pknu.ac.kr/research/rm_hdr.html)
##### Robust High Dynamic Range Imaging by Rank Minimization (TH Oh, JY Lee, et al. TPAMI 2015) [[web]](http://web.mit.edu/taehyun/www/Research/RHDR/RHDR.htm)

### Deep Learning
##### Deep High Dynamic Range Imaging of Dynamic Scenes (NK Kalantari, R Ramamoorthi. SIGGRAPH 2017) [[web]](http://cseweb.ucsd.edu/~viscomp/projects/SIG17HDR/)
##### End-to-End Deep HDR Imaging with Large Foreground Motions (S Wu, J Xu, et al. 2017) (Deep High Dynamic Range Imaging with Large Foreground Motions. ECCV 2018) [[web]](https://elliottwu.com/projects/hdr/)
##### Attention-guided Network for Ghost-free High Dynamic Range Imaging (Q Yan, D Gong, et al. 2018) [[web]](https://donggong1.github.io/ahdr.html)
##### Towards Practical and Efficient High-Resolution HDR Deghosting with CNN (K. Ram Prabhakar, Susmit Agrawal, et al. CVPR 2020) [[web]](http://val.serc.iisc.ernet.in/HDR/eccv20/)
##### Deep HDR Imaging via A Non-local Network (Q Yan, L Zhang, et al. TIP 2020) [[paper]](https://qingsenyangit.github.io/publication/tip20/)
##### NTIRE 2021 Challenge on High Dynamic Range Imaging: Dataset, Methods and Results [[paper]](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Perez-Pellitero_NTIRE_2021_Challenge_on_High_Dynamic_Range_Imaging_Dataset_Methods_CVPRW_2021_paper.html)
##### ADNet: Attention-guided Deformable Convolutional Network for High Dynamic Range Imaging (Zhen Liu, Wenjie Lin, et al. CVPRW 2021) [[github]](https://github.com/liuzhen03/ADNet)
##### NTIRE 2022 Challenge on High Dynamic Range Imaging: Methods and Results [[paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Perez-Pellitero_NTIRE_2022_Challenge_on_High_Dynamic_Range_Imaging_Methods_and_CVPRW_2022_paper.pdf)
##### Multi-Bracket High Dynamic Range Imaging with Event Cameras (Nico Messikommer, Stamatios Georgoulis, et al. CVPRW 2022)[[paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Messikommer_Multi-Bracket_High_Dynamic_Range_Imaging_With_Event_Cameras_CVPRW_2022_paper.pdf)
##### UltraFusion: Ultra High Dynamic Imaging using Exposure Fusion (Zixuan Chen, Yujin Wang, et al. CVPR 2025) [[web]](https://ultrafusion.openxlab.org.cn/home)

### Google Project
##### (HDR+) Burst photography for high dynamic range and low-light imaging on mobile cameras (SW Hasinoff, D Sharlet, et al. ToG 2016) [[web]](https://hdrplusdata.org/)
##### (Night sight) Handheld Mobile Photography in Very Low Light (O Liba, K Murthy, et al. SIGGRAPH Asia 2019) [[github]](https://github.com/google/night-sight/tree/master/docs)


## Survey and Evaluate
### Metric
##### HDR-VDP-2: A calibrated visual metric for visibility and quality predictions in all luminance conditions (R Mantiuk, KJ Kim, et al. ToG 2011) [[web]](https://www.cs.ubc.ca/nest/imager/tr/2011/Mantiuk_HDR-VDP-2/)
##### An Objective Deghosting Quality Metric for HDR Images (OT Tursun, AO Akyüz, et al. Eurographics 2016) [[web]](https://user.ceng.metu.edu.tr/~akyuz/files/eg2016/index.html)
### Survey
##### The State of the Art in HDR Deghosting A Survey and Evaluation (OT Tursun, AO Akyüz, et al. 2015) [[paper]](https://web.cs.hacettepe.edu.tr/~erkut/publications/HDR-deghosting-star.pdf)
##### Deep Learning for HDR Imaging: State-of-the-Art and Future Trends (Lin Wang, Kuk-Jin Yoon. 2021) [[paper]](https://arxiv.org/pdf/2110.10394.pdf)
### Benchmark
##### http://www.vsislab.com/projects/IPM/HDR/project.html
##### NTIRE 2021 Challenge on High Dynamic Range Imaging:[[web]](https://data.vision.ee.ethz.ch/cvl/ntire21/)[[paper]](https://openaccess.thecvf.com/content/CVPR2021W/NTIRE/html/Perez-Pellitero_NTIRE_2021_Challenge_on_High_Dynamic_Range_Imaging_Dataset_Methods_CVPRW_2021_paper.html)
##### NTIRE 2022 Challenge on High Dynamic Range Imaging:[[web]](https://data.vision.ee.ethz.ch/cvl/ntire22/)[[paper]](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Perez-Pellitero_NTIRE_2022_Challenge_on_High_Dynamic_Range_Imaging_Methods_and_CVPRW_2022_paper.pdf)

