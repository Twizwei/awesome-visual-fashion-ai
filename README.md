# awesome-visual-fashion-ai

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A repo about visual fashion AI. This repo is inspired by [Ayushi Dalmia](https://github.com/ayushidalmia/awesome-fashion-ai) and [Tzu-Heng Lin](https://github.com/lzhbrian/Cool-Fashion-Papers). Note that the research areas below might be overlapped.

## Contents

* [Papers](#papers)
* [Websites](#websites)
* [Tutorials/Workshops](#tutorials/workshops)
* [Datasets](#datasets)
* [Miscellaneous](#miscellaneous)


### Papers

#### Visual Recommendations/Visual Retrieval/Compatibility/Embeddings

  - [ViBE: Dressing for Diverse Body Shapes](https://arxiv.org/abs/1912.06697), CVPR 2020 (oral)
  - [Compatible and Diverse Fashion Image Inpainting](http://openaccess.thecvf.com/content_ICCV_2019/papers/Han_FiNet_Compatible_and_Diverse_Fashion_Image_Inpainting_ICCV_2019_paper.pdf) ICCV 2019 (oral)
  - [Multi-Similarity Loss with General Pair Weighting for Deep Metric Learning](https://arxiv.org/pdf/1904.06627.pdf) CVPR 2019, [code](https://github.com/MalongTech/research-ms-loss)
  - [Context-Aware Visual Compatibility Prediction](https://arxiv.org/abs/1902.03646) CVPR 2019, [code](https://github.com/gcucurull/visual-compatibility)
  - [POG: Personalized Outfit Generation for Fashion Recommendation at Alibaba iFashion](https://arxiv.org/abs/1905.01866) KDD 2019
  - [Creating Capsule Wardrobes from Fashion Images](https://arxiv.org/abs/1712.02662), CVPR 2018 (spotlight)
  - [Learning Fashion Compatibility with Bidirectional LSTMs](https://arxiv.org/abs/1707.05691) ACM MM'17, [code](https://github.com/xthan/polyvore)
  - [Learning Type-Aware Embeddings for Fashion Compatibility](https://arxiv.org/abs/1803.09196) ECCV 2018
  - [Learning Attribute Representations with Localization for Flexible Fashion Search](http://openaccess.thecvf.com/content_cvpr_2018/papers_backup/Ak_Learning_Attribute_Representations_CVPR_2018_paper.pdf) CVPR 2018
  - [Learning the Latent "Look": Unsupervised Discovery of a Style-Coherent Embedding from Fashion Images](https://arxiv.org/abs/1707.03376) ICCV 2017, [project page](http://vision.cs.utexas.edu/projects/StyleEmbedding/), [code](https://github.com/wlhsiao/Mallet)
  - [Automatic Spatially-aware Fashion Concept Discovery](http://users.umiacs.umd.edu/~xintong/publications/automatic-fashion-concept-final.pdf) ICCV 2017, [data](https://github.com/xthan/fashion-200k/)

  
#### Try-ons/Synthesis
  - [GAN-based Garment Generation Using Sewing Pattern Images](http://www.cs.umd.edu/~yushen/docs/ECCV2020.pdf), [project page](https://gamma.umd.edu/researchdirections/virtualtryon/garmentgeneration/), [code](https://github.com/YuShen0118/Garment_Generation), [data](https://drive.google.com/drive/folders/1GR9cut1Ip7T3R-nYnuWPJUSarX8MT_xY)
  - [Fashion Editing with Adversarial Parsing Learning](http://openaccess.thecvf.com/content_CVPR_2020/papers/Dong_Fashion_Editing_With_Adversarial_Parsing_Learning_CVPR_2020_paper.pdf) CVPR 2020 
  - [Image Based Virtual Try-on Network from Unpaired Data](http://openaccess.thecvf.com/content_CVPR_2020/papers/Neuberger_Image_Based_Virtual_Try-On_Network_From_Unpaired_Data_CVPR_2020_paper.pdf) CVPR 2020
  - [Towards Photo-Realistic Virtual Try-On by Adaptively Generating↔Preserving Image Content](https://arxiv.org/abs/2003.05863) CVPR 2020, [code](https://github.com/switchablenorms/DeepFashion_Try_On)
  - [Fashion++: Minimal Edits for Outfit Improvement](https://arxiv.org/abs/1904.09261) ICCV 2019, [project page](http://vision.cs.utexas.edu/projects/FashionPlus/)
  - [M2E-Try On Net: Fashion from Model to Everyone](https://arxiv.org/pdf/1811.08599.pdf) ACM MM'19
  - [VITON: An Image-based Virtual Try-on Network](https://arxiv.org/abs/1711.08447) CVPR 2018, [code](https://github.com/xthan/VITON)
  - [ClothFlow: A Flow-Based Model for Clothed Person Generation](http://openaccess.thecvf.com/content_ICCV_2019/papers/Han_ClothFlow_A_Flow-Based_Model_for_Clothed_Person_Generation_ICCV_2019_paper.pdf) ICCV 2019
  - [Be Your Own Prada: Fashion Synthesis with Structural Coherence](https://arxiv.org/abs/1710.07346) ICCV 2017, [project page](http://mmlab.ie.cuhk.edu.hk/projects/FashionGAN/), [code and data](https://github.com/zhusz/ICCV17-fashionGAN)

#### Makeups/Faces
 - [PSGAN: Pose and Expression Robust Spatial-Aware GAN for Customizable
Makeup Transfer](https://arxiv.org/abs/1909.06956) CVPR 2020 (oral), [code](https://github.com/wtjiang98/PSGAN)
 - [Beautyglow : On-demand makeup transfer framework with reversible generative network](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_BeautyGlow_On-Demand_Makeup_Transfer_Framework_With_Reversible_Generative_Network_CVPR_2019_paper.pdf), [code](https://github.com/BeautyGlow/BeautyGlow.github.io/tree/master/source%20code), [demo](https://beautyglow.github.io/)
 - [LADN: Local Adversarial Disentangling Network for Facial Makeup and De-Makeup](https://arxiv.org/abs/1904.11272) ICCV 2019, [code](https://github.com/wangguanzhi/LADN)
 - [Beholder-Gan: Generation and Beautification of Facial Images with Conditioning on Their Beauty Level](https://ieeexplore.ieee.org/abstract/document/8803807?casa_token=O7fSylZrOSIAAAAA:g_9xCCNceTSSYQ0oD9X6u003mrdWUTqxyN1lR9XE2XlMfqKCEv2Y-zdh8xnysfta6MIxwl5C0WQ) ICIP 2019, [code](https://github.com/beholdergan/Beholder-GAN)
 - [Semi-supervised Eye Makeup Transfer by Swapping Learned Representation](http://openaccess.thecvf.com/content_ICCVW_2019/papers/LCI/Zhu_Semi-Supervised_Eye_Makeup_Transfer_by_Swapping_Learned_Representation_ICCVW_2019_paper.pdf) ICCV 2019 Workshop
 - [Disentangled Makeup Transfer with Generative Adversarial Network](https://arxiv.org/abs/1907.01144), [code](https://github.com/Honlan/DMT)
 - [PairedCycleGAN: Asymmetric Style Transfer for Applying and Removing Makeup](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chang_PairedCycleGAN_Asymmetric_Style_CVPR_2018_paper.pdf) CVPR 2018
 - [BeautyGAN: Instance-level Facial Makeup Transfer with Deep Generative Adversarial Network
](http://liusi-group.com/pdf/BeautyGAN-camera-ready_2.pdf) ACM MM'18, [code](https://github.com/wtjiang98/BeautyGAN_pytorch)
 - [Anti-Makeup: Learning A Bi-Level Adversarial Network for Makeup-Invariant Face Verification](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/16739) AAAI 18
 - [Examples-Rules Guided Deep Neural Network for Makeup Recommendation](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14773) AAAI 17
 - [Makeup like a superstar: Deep Localized Makeup Transfer Network](https://arxiv.org/abs/1604.07102), IJCAI 2016
 - [Simulating Makeup through Physics-based Manipulation of Intrinsic Image Layers](http://openaccess.thecvf.com/content_cvpr_2015/papers/Li_Simulating_Makeup_Through_2015_CVPR_paper.pdf) CVPR 2015
 - ["Wow! you are so beautiful today!"](https://dl.acm.org/doi/10.1145/2502081.2502126) ACM MM'13
 - [Digital Face Makeup by Example](https://www.comp.nus.edu.sg/~tsim/documents/face_makeup_cvpr09_lowres.pdf) CVPR 2009

### Websites

- [AI for Fashion](https://cognitivefashion.github.io/).


### Tutorials/Workshops

* ICCV/ECCV/CVPR Workshop on Computer Vision for Fashion, Art and Design, CVPR [2020](https://sites.google.com/view/cvcreative2020/home?authuser=0), ICCV [2019](https://sites.google.com/view/cvcreative), ECCV [2018](https://sites.google.com/view/eccvfashion/), ICCV [2017](https://sites.google.com/zalando.de/cvf-iccv2017/home?authuser=0)

### Datasets/Toolbox

* [Deep Fashion3D](https://kv2000.github.io/2020/03/25/deepFashion3DRevisited/), [paper](https://arxiv.org/pdf/2003.12753v1.pdf)
* [Fashionpedia](https://fashionpedia.github.io/home/), [paper](https://arxiv.org/abs/2004.12276)
* [DeepFashion2](https://github.com/switchablenorms/DeepFashion2), [challenge](https://sites.google.com/view/cvcreative2020/program/deepfashion2-challenge?authuser=0), [paper](https://arxiv.org/abs/1901.07973)
* [DeepFashion](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html), [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Liu_DeepFashion_Powering_Robust_CVPR_2016_paper.pdf)
* [FashionIQ](https://github.com/XiaoxiaoGuo/fashion-iq), [challenge](https://sites.google.com/view/cvcreative2020/fashion-iq?authuser=0), [paper](https://arxiv.org/abs/1905.12794)
* [GeoStyle](https://geostyle.cs.cornell.edu/), [paper](https://geostyle.cs.cornell.edu/static/pdf/geostyle.pdf), [code](https://github.com/kavitabala/geostyle)
* [Polyvore Dataset](https://github.com/xthan/polyvore-dataset)
* [MMFashion](https://github.com/open-mmlab/mmfashion)

### Miscellaneous
* [Face Parsing](https://github.com/zllrunning/face-parsing.PyTorch)
* [Fashion Captioning: Towards Generating Accurate Descriptions with Semantic Rewards](), [code](https://github.com/xuewyang/Fashion_Captioning)


