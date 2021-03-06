# da_litrature

#contents
- [Unsupervised DA](#unsupervised-da)
    - [Adversarial Methods](#adversarial-methods)
    - [Distance-based Methods](#distance-based-methods)
## Unsupervised DA

### Adversarial Methods

**Conference**
- Adversarial-Learned Loss for Domain Adaptation [[AAAI2020]](https://arxiv.org/abs/2001.01046v1)
- Adversarial Domain Adaptation with Domain Mixup [[AAAI2020]](https://arxiv.org/abs/1912.01805v1) [[Pytorch]](https://github.com/ChrisAllenMing/Mixup_for_UDA)
- Discriminative Adversarial Domain Adaptation [[AAAI2020]](https://arxiv.org/abs/1911.12036v1) [[Pytorch]](https://github.com/huitangtang/DADA-AAAI2020)
- Unifying Unsupervised Domain Adaptation and Zero-Shot Visual Recognition [[IJCNN2019]](https://arxiv.org/abs/1903.10601) [[Matlab]](https://github.com/hellowangqian/domain-adaptation-capls)
- Transfer Learning with Dynamic Adversarial Adaptation Network [[ICDM2019]](https://arxiv.org/abs/1909.08184)
- Joint Adversarial Domain Adaptation [[ACM MM2019]](https://dl.acm.org/citation.cfm?id=3351070)
- Cycle-consistent Conditional Adversarial Transfer Networks [[ACM MM2019]](https://dl.acm.org/citation.cfm?id=3350902) [[Pytorch]](https://github.com/lijin118/3CATN)
- Learning Disentangled Semantic Representation for Domain Adaptation [[IJCAI2019]](https://www.ijcai.org/proceedings/2019/0285.pdf) [[Tensorflow]](https://github.com/DMIRLAB-Group/DSR)
- Transferability vs. Discriminability: Batch Spectral Penalization for Adversarial Domain Adaptation [[ICML2019]](http://proceedings.mlr.press/v97/chen19i/chen19i.pdf) [[Pytorch]](https://github.com/thuml/Batch-Spectral-Penalization)
- Transferable Adversarial Training: A General Approach to Adapting Deep Classifiers [[ICML2019]](http://proceedings.mlr.press/v97/liu19b/liu19b.pdf) [[Pytorch]](https://github.com/thuml/Transferable-Adversarial-Training)
- Drop to Adapt: Learning Discriminative Features for Unsupervised Domain Adaptation [[ICCV2019]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lee_Drop_to_Adapt_Learning_Discriminative_Features_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf) [[PyTorch]](https://github.com/postBG/DTA.pytorch)
- Cluster Alignment with a Teacher for Unsupervised Domain Adaptation [[ICCV2019]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Deng_Cluster_Alignment_With_a_Teacher_for_Unsupervised_Domain_Adaptation_ICCV_2019_paper.pdf) [[Tensorflow]](https://github.com/thudzj/CAT)
- Unsupervised Domain Adaptation via Regularized Conditional Alignment [[ICCV2019]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Cicek_Unsupervised_Domain_Adaptation_via_Regularized_Conditional_Alignment_ICCV_2019_paper.pdf)
- Attending to Discriminative Certainty for Domain Adaptation [[CVPR2019]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Kurmi_Attending_to_Discriminative_Certainty_for_Domain_Adaptation_CVPR_2019_paper.pdf) [[Project]](https://delta-lab-iitk.github.io/CADA/)
- GCAN: Graph Convolutional Adversarial Network for Unsupervised Domain Adaptation [[CVPR2019]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ma_GCAN_Graph_Convolutional_Adversarial_Network_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf)
- Domain-Symmetric Networks for Adversarial Domain Adaptation [[CVPR2019]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Domain-Symmetric_Networks_for_Adversarial_Domain_Adaptation_CVPR_2019_paper.pdf) [[Pytorch]](https://github.com/YBZh/SymNets)
- DLOW: Domain Flow for Adaptation and Generalization [[CVPR2019 Oral]](https://arxiv.org/pdf/1812.05418.pdf)
- Progressive Feature Alignment for Unsupervised Domain Adaptation [[CVPR2019]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Progressive_Feature_Alignment_for_Unsupervised_Domain_Adaptation_CVPR_2019_paper.pdf) [[Tensorflow]](https://github.com/Xiewp/PFAN)
- Gotta Adapt ’Em All: Joint Pixel and Feature-Level Domain Adaptation for Recognition in the Wild [[CVPR2019]](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tran_Gotta_Adapt_Em_All_Joint_Pixel_and_Feature-Level_Domain_Adaptation_CVPR_2019_paper.pdf) 
- Looking back at Labels: A Class based Domain Adaptation Technique [[IJCNN2019]](https://arxiv.org/abs/1904.01341) [[Project]](https://vinodkkurmi.github.io/DiscriminatorDomainAdaptation/)
- Consensus Adversarial Domain Adaptation [[AAAI2019]](https://aaai.org/ojs/index.php/AAAI/article/view/4552)
- Transferable Attention for Domain Adaptation [[AAAI2019]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/transferable-attention-aaai19.pdf)
- Exploiting Local Feature Patterns for Unsupervised Domain Adaptation [[AAAI2019]](https://arxiv.org/abs/1811.05042v2)
- Augmented Cyclic Adversarial Learning for Low Resource Domain Adaptation [[ICLR2019]](https://openreview.net/forum?id=B1G9doA9F7)
- Conditional Adversarial Domain Adaptation [[NIPS2018]](http://papers.nips.cc/paper/7436-conditional-adversarial-domain-adaptation) [[Pytorch(official)]](https://github.com/thuml/CDAN)  [[Pytorch(third party)]](https://github.com/thuml/CDAN)
- Semi-supervised Adversarial Learning to Generate Photorealistic Face Images of New Identities from 3D Morphable Model [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Baris_Gecer_Semi-supervised_Adversarial_Learning_ECCV_2018_paper.pdf)
- Deep Adversarial Attention Alignment for Unsupervised Domain Adaptation: the Benefit of Target Expectation Maximization [[ECCV2018]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Guoliang_Kang_Deep_Adversarial_Attention_ECCV_2018_paper.pdf)
- Learning Semantic Representations for Unsupervised Domain Adaptation [[ICML2018]](http://proceedings.mlr.press/v80/xie18c.html) [[TensorFlow(Official)]](https://github.com/Mid-Push/Moving-Semantic-Transfer-Network)
- CyCADA: Cycle-Consistent Adversarial Domain Adaptation [[ICML2018]](http://proceedings.mlr.press/v80/hoffman18a.html) [[Pytorch(official)]](https://github.com/jhoffman/cycada_release)
- From source to target and back: Symmetric Bi-Directional Adaptive GAN [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Russo_From_Source_to_CVPR_2018_paper.pdf) [[Keras(Official)]](https://github.com/engharat/SBADAGAN) [[Pytorch]](https://github.com/naoto0804/pytorch-SBADA-GAN)
- Detach and Adapt: Learning Cross-Domain Disentangled Deep Representation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_Detach_and_Adapt_CVPR_2018_paper.pdf) [[Tensorflow]](https://github.com/ycliu93/CDRD)
- Maximum Classifier Discrepancy for Unsupervised Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Saito_Maximum_Classifier_Discrepancy_CVPR_2018_paper.pdf) [[Pytorch(Official)]](https://github.com/mil-tokyo/MCD_DA)
- Adversarial Feature Augmentation for Unsupervised Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1711.08561) [[TensorFlow(Official)]](https://github.com/ricvolpi/adversarial-feature-augmentation)
- Duplex Generative Adversarial Network for Unsupervised Domain Adaptation [[CVPR2018]](http://vipl.ict.ac.cn/uploadfile/upload/2018041610083083.pdf) [[Pytorch(Official)]](http://vipl.ict.ac.cn/view_database.php?id=6)
- Generate To Adapt: Aligning Domains using Generative Adversarial Networks [[CVPR2018]](https://arxiv.org/abs/1704.01705) [[Pytorch(Official)]](https://github.com/yogeshbalaji/Generate_To_Adapt)
- Image to Image Translation for Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1712.00479)
- Unsupervised Domain Adaptation with Similarity Learning [[CVPR2018]](https://arxiv.org/abs/1711.08995)
- Conditional Generative Adversarial Network for Structured Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hong_Conditional_Generative_Adversarial_CVPR_2018_paper.pdf) 
- Collaborative and Adversarial Network for Unsupervised Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Collaborative_and_Adversarial_CVPR_2018_paper.pdf) [[Pytorch]](https://github.com/zhangweichen2006/iCAN)
- Re-Weighted Adversarial Adaptation Network for Unsupervised Domain Adaptation [[CVPR2018]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Re-Weighted_Adversarial_Adaptation_CVPR_2018_paper.pdf)
- Multi-Adversarial Domain Adaptation [[AAAI2018]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/multi-adversarial-domain-adaptation-aaai18.pdf) [[Caffe(Official)]](https://github.com/thuml/MADA)
- Wasserstein Distance Guided Representation Learning for Domain Adaptation [[AAAI2018]](https://arxiv.org/abs/1707.01217) [[TensorFlow(official)]](https://github.com/RockySJ/WDGRL) [[Pytorch]](https://github.com/jvanvugt/pytorch-domain-adaptation)
- Incremental Adversarial Domain Adaptation for Continually Changing Environments [[ICRA2018]](https://arxiv.org/abs/1712.07436)
- Adversarial Dropout Regularization [[ICLR2018]](https://openreview.net/forum?id=HJIoJWZCZ)
- A DIRT-T Approach to Unsupervised Domain Adaptation [[ICLR2018 Poster]](https://openreview.net/forum?id=H1q-TM-AW) [[Tensorflow(Official)]](https://github.com/RuiShu/dirt-t)
- Label Efficient Learning of Transferable Representations acrosss Domains and Tasks [[NIPS2017]](http://vision.stanford.edu/pdf/luo2017nips.pdf) [[Project]](http://alan.vision/nips17_website/)
- Adversarial Discriminative Domain Adaptation [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tzeng_Adversarial_Discriminative_Domain_CVPR_2017_paper.pdf)  [[Tensorflow(Official)]](https://github.com/erictzeng/adda) [[Pytorch]](https://github.com/corenel/pytorch-adda)
- Unsupervised Pixel–Level Domain Adaptation with Generative Adversarial Networks [[CVPR2017]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Bousmalis_Unsupervised_Pixel-Level_Domain_CVPR_2017_paper.pdf) [[Tensorflow(Official)]](https://github.com/tensorflow/models/tree/master/research/domain_adaptation) [[Pytorch]](https://github.com/vaibhavnaagar/pixelDA_GAN)
- Domain Separation Networks [[NIPS2016]](http://papers.nips.cc/paper/6254-domain-separation-networks)
- Deep Reconstruction-Classification Networks for Unsupervised Domain Adaptation [[ECCV2016]](https://arxiv.org/abs/1607.03516)
- Domain-Adversarial Training of Neural Networks [[JMLR2016]](http://www.jmlr.org/papers/volume17/15-239/15-239.pdf)
- Unsupervised Domain Adaptation by Backpropagation [[ICML2015]](http://proceedings.mlr.press/v37/ganin15.pdf) [[Caffe(Official)]](https://github.com/ddtm/caffe/tree/grl) [[Tensorflow]](https://github.com/shucunt/domain_adaptation) [[Pytorch]](https://github.com/fungtion/DANN)

**Journal**
- Adversarial Learning and Interpolation Consistency for Unsupervised Domain Adaptation [[IEEE ACCESS]](https://ieeexplore.ieee.org/document/8913529)
- TarGAN: Generating target data with class labels for unsupervised domain adaptation [[Knowledge-Based Systems]]()

**Arxiv**
- Bi-Directional Generation for Unsupervised Domain Adaptation [[12 Feb 2020]](https://arxiv.org/abs/2002.04869v1)
- Enlarging Discriminative Power by Adding an Extra Class in Unsupervised Domain Adaptation [[19 Feb 2020]](https://arxiv.org/abs/2002.08041v1) [[Tensorflow]](https://github.com/haitran14/gada)
- Learning Domain Adaptive Features with Unlabeled Domain Bridges [[10 Dec 2019]](https://arxiv.org/abs/1912.05004v1)
- Reducing Domain Gap via Style-Agnostic Networks [[25 Oct 2019]](https://arxiv.org/abs/1910.11645)
- Generalized Domain Adaptation with Covariate and
Label Shift CO-ALignment [[23 Oct 2019]](https://arxiv.org/abs/1910.10320)
- Adversarial Variational Domain Adaptation [[25 Sep 2019]](https://arxiv.org/abs/1909.11651)
- Contrastively Smoothed Class Alignment for Unsupervised Domain Adaptation [[arXiv 13 Sep 2019]](https://arxiv.org/abs/1909.05288)
- SALT: Subspace Alignment as an Auxiliary Learning Task for Domain Adaptation [[arXiv 11 Jun 2019]](https://arxiv.org/abs/1906.04338v1)
- Joint Semantic Domain Alignment and Target Classifier Learning for Unsupervised Domain Adaptation [[arXiv 10 Jun 2019]](https://arxiv.org/abs/1906.04053v1)
- Adversarial Domain Adaptation Being Aware of Class Relationships [[arXiv 28 May 2019]](https://arxiv.org/abs/1905.11931v1)
- Domain-Invariant Adversarial Learning for Unsupervised Domain Adaption [[arXiv 30 Nov 2018]](https://arxiv.org/abs/1811.12751)
- Unsupervised Domain Adaptation using Deep Networks with Cross-Grafted Stacks [[arXiv 17 Feb 2019]](https://arxiv.org/abs/1902.06328v1)
- DART: Domain-Adversarial Residual-Transfer Networks for Unsupervised Cross-Domain Image Classification [[arXiv 30 Dec 2018]](https://arxiv.org/abs/1812.11478)
- Unsupervised Domain Adaptation using Generative Models and Self-ensembling [[arXiv 2 Dec 2018]](https://arxiv.org/abs/1812.00479)
- Domain Confusion with Self Ensembling for Unsupervised Adaptation [[arXiv 10 Oct 2018]](https://arxiv.org/abs/1810.04472)
- Improving Adversarial Discriminative Domain Adaptation [[arXiv 10 Sep 2018]](https://arxiv.org/abs/1809.03625)
- M-ADDA: Unsupervised Domain Adaptation with Deep Metric Learning [[arXiv 6 Jul 2018]](https://arxiv.org/abs/1807.02552v1) [[Pytorch(official)]](https://github.com/IssamLaradji/M-ADDA)
- Factorized Adversarial Networks for Unsupervised Domain Adaptation [[arXiv 4 Jun 2018]](https://arxiv.org/abs/1806.01376v1)
- DiDA: Disentangled Synthesis for Domain Adaptation [[arXiv 21 May 2018]](https://arxiv.org/abs/1805.08019v1)
- Unsupervised Domain Adaptation with Adversarial Residual Transform Networks [[arXiv 25 Apr 2018]](https://arxiv.org/abs/1804.09578)
- Causal Generative Domain Adaptation Networks [[arXiv 28 Jun 2018]](https://arxiv.org/abs/1804.04333v3)


### Distance-based Methods
**Journal**

- Transferable Representation Learning with Deep Adaptation Networks [[TPAMI]](https://ieeexplore.ieee.org/document/8454781)

**Conference**
- HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation [[AAAI2020]](https://arxiv.org/abs/1912.11976) [[Tensorflow]](https://github.com/chenchao666/HoMM-Master)
- Normalized Wasserstein for Mixture Distributions With Applications in Adversarial Learning and Domain Adaptation [[ICCV2019]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Balaji_Normalized_Wasserstein_for_Mixture_Distributions_With_Applications_in_Adversarial_Learning_ICCV_2019_paper.pdf)
- Joint Domain Alignment and Discriminative Feature Learning for Unsupervised Deep Domain Adaptation [[AAAI2019]](https://arxiv.org/abs/1808.09347v2)
- Residual Parameter Transfer for Deep Domain Adaptation [[CVPR2018]](https://arxiv.org/abs/1711.07714)
- Deep Asymmetric Transfer Network for Unbalanced Domain Adaptation [[AAAI2018]](http://media.cs.tsinghua.edu.cn/~multimedia/cuipeng/papers/DATN.pdf)
- Central Moment Discrepancy for Unsupervised Domain Adaptation [[ICLR2017]](https://openreview.net/pdf?id=SkB-_mcel), [[InfSc2019]](https://arxiv.org/pdf/1711.06114.pdf), [[code]](https://github.com/wzell/cmd)
- Deep CORAL: Correlation Alignment for Deep Domain Adaptation [[ECCV2016]](https://arxiv.org/abs/1607.01719)
- Learning Transferable Features with Deep Adaptation Networks [[ICML2015]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/deep-adaptation-networks-icml15.pdf)[[code]](https://github.com/thuml/DAN)
- Unsupervised Domain Adaptation with Residual Transfer Networks [[NIPS2016]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/residual-transfer-network-nips16.pdf) [[code]](https://github.com/thuml/Xlearn)
- Deep Transfer Learning with Joint Adaptation Networks [[ICML2017]](http://ise.thss.tsinghua.edu.cn/~mlong/doc/joint-adaptation-networks-icml17.pdf) [[code]](https://github.com/thuml/Xlearn)
