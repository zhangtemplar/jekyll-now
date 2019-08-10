---
layout: post
title: Face Reconstruction in CVPR 2019
tags: deep-learning face-reconstruction 3dmm
---

![](http://cvlab.cse.msu.edu/images/reconstructionTeaser.png)

# [MMFace: A Multi-Metric Regression Network for Unconstrained Face Reconstruction](http://openaccess.thecvf.com/content_CVPR_2019/html/Yi_MMFace_A_Multi-Metric_Regression_Network_for_Unconstrained_Face_Reconstruction_CVPR_2019_paper.html)
> [Hongwei Yi](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Chen Li](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Qiong Cao](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Xiaoyong Shen](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Sheng Li](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Guoping Wang](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Yu-Wing Tai](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yi_MMFace_A_Multi-Metric_Regression_Network_for_Unconstrained_Face_Reconstruction_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Yi_MMFace_A_Multi-Metric_CVPR_2019_supplemental.pdf)

> We propose to address the face reconstruction in the wild by using a multi-metric regression network, MMFace, to align a 3D face morphable model (3DMM) to an input image. The key idea is to utilize a volumetric sub-network to estimate an intermediate geometry representation, and a parametric sub-network to regress the 3DMM parameters. Our parametric sub-network consists of identity loss, expression loss, and pose loss which greatly improves the aligned geometry details by incorporating high level loss functions directly defined in the 3DMM parametric spaces. Our high-quality reconstruction is robust under large variations of expressions, poses, illumination conditions, and even with large partial occlusions. We evaluate our method by comparing the performance with state-of-the-art approaches on latest 3D face dataset LS3D-W and Florence. We achieve significant improvements both quantitatively and qualitatively. Due to our high-quality reconstruction, our method can be easily extended to generate high-quality geometry sequences for video inputs.

# [GANFIT: Generative Adversarial Network Fitting for High Fidelity 3D Face Reconstruction](http://openaccess.thecvf.com/content_CVPR_2019/html/Gecer_GANFIT_Generative_Adversarial_Network_Fitting_for_High_Fidelity_3D_Face_CVPR_2019_paper.html)
> [Baris Gecer](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Stylianos Ploumpis](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Irene Kotsia](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Stefanos Zafeiriou](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gecer_GANFIT_Generative_Adversarial_Network_Fitting_for_High_Fidelity_3D_Face_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Gecer_GANFIT_Generative_Adversarial_CVPR_2019_supplemental.pdf)

> In the past few years, a lot of work has been done towards reconstructing the 3D facial structure from single images by capitalizing on the power of Deep Convolutional Neural Networks (DCNNs). In the most recent works, differentiable renderers were employed in order to learn the relationship between the facial identity features and the parameters of a 3D morphable model for shape and texture. The texture features either correspond to components of a linear texture space or are learned by auto-encoders directly from in-the-wild images. In all cases, the quality of the facial texture reconstruction of the state-of-the-art methods is still not capable of modeling textures in high fidelity. In this paper, we take a radically different approach and harness the power of Generative Adversarial Networks (GANs) and DCNNs in order to reconstruct the facial texture and shape from single images. That is, we utilize GANs to train a very powerful generator of facial texture in UV space. Then, we revisit the original 3D Morphable Models (3DMMs) fitting approaches making use of non-linear optimization to find the optimal latent parameters that best reconstruct the test image but under a new perspective. We optimize the parameters with the supervision of pretrained deep identity features through our end-to-end differentiable framework. We demonstrate excellent results in photorealistic and identity preserving 3D face reconstructions and achieve for the first time, to the best of our knowledge, facial texture reconstruction with high-frequency details.

# [MVF-Net: Multi-View 3D Face Morphable Model Regression](http://openaccess.thecvf.com/content_CVPR_2019/html/Wu_MVF-Net_Multi-View_3D_Face_Morphable_Model_Regression_CVPR_2019_paper.html)
> [Fanzi Wu](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Linchao Bao](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Yajing Chen](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Yonggen Ling](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Yibing Song](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Songnan Li](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[King Ngi Ngan](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Wei Liu](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wu_MVF-Net_Multi-View_3D_Face_Morphable_Model_Regression_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Wu_MVF-Net_Multi-View_3D_CVPR_2019_supplemental.zip)

> We address the problem of recovering the 3D geometry of a human face from a set of facial images in multiple views. While recent studies have shown impressive progress in 3D Morphable Model (3DMM) based facial reconstruction, the settings are mostly restricted to a single view. There is an inherent drawback in the single-view setting: the lack of reliable 3D constraints can cause unresolvable ambiguities. We in this paper explore 3DMM-based shape recovery in a different setting, where a set of multi-view facial images are given as input. A novel approach is proposed to regress 3DMM parameters from multi-view inputs with an end-to-end trainable Convolutional Neural Network (CNN). Multi-view geometric constraints are incorporated into the network by establishing dense correspondences between different views leveraging a novel self-supervised view alignment loss. The main ingredient of the view alignment loss is a differentiable dense optical flow estimator that can backpropagate the alignment errors between an input view and a synthetic rendering from another input view, which is projected to the target view through the 3D shape to be inferred. Through minimizing the view alignment loss, better 3D shapes can be recovered such that the synthetic projections from one view to another can better align with the observed image. Extensive experiments demonstrate the superiority of the proposed method over other 3DMM methods.

# [Joint Face Detection and Facial Motion Retargeting for Multiple Faces](http://openaccess.thecvf.com/content_CVPR_2019/html/Chaudhuri_Joint_Face_Detection_and_Facial_Motion_Retargeting_for_Multiple_Faces_CVPR_2019_paper.html)
> [Bindita Chaudhuri](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Noranart Vesdapunt](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Baoyuan Wang](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chaudhuri_Joint_Face_Detection_and_Facial_Motion_Retargeting_for_Multiple_Faces_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Chaudhuri_Joint_Face_Detection_CVPR_2019_supplemental.pdf)

> Facial motion retargeting is an important problem in both computer graphics and vision, which involves capturing the performance of a human face and transferring it to another 3D character. Learning 3D morphable model (3DMM) parameters from 2D face images using convolutional neural networks is common in 2D face alignment, 3D face reconstruction etc. However, existing methods either require an additional face detection step before retargeting or use a cascade of separate networks to perform detection followed by retargeting in a sequence. In this paper, we present a single end-to-end network to jointly predict the bounding box locations and 3DMM parameters for multiple faces. First, we design a novel multitask learning framework that learns a disentangled representation of 3DMM parameters for a single face. Then, we leverage the trained single face model to generate ground truth 3DMM parameters for multiple faces to train another network that performs joint face detection and motion retargeting for images with multiple faces. Experimental results show that our joint detection and retargeting network has high face detection accuracy and is robust to extreme expressions and poses while being faster than state-of-the-art methods.

# [Expressive Body Capture: 3D Hands, Face, and Body From a Single Image](http://openaccess.thecvf.com/content_CVPR_2019/html/Pavlakos_Expressive_Body_Capture_3D_Hands_Face_and_Body_From_a_CVPR_2019_paper.html)
> [Georgios Pavlakos](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Vasileios Choutas](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Nima Ghorbani](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Timo Bolkart](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Ahmed A. A. Osman](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Dimitrios Tzionas](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Michael J. Black](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pavlakos_Expressive_Body_Capture_3D_Hands_Face_and_Body_From_a_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Pavlakos_Expressive_Body_Capture_CVPR_2019_supplemental.pdf)

> To facilitate the analysis of human actions, interactions and emotions, we compute a 3D model of human body pose, hand pose, and facial expression from a single monocular image. To achieve this, we use thousands of 3D scans to train a new, unified, 3D model of the human body, SMPL-X, that extends SMPL with fully articulated hands and an expressive face. Learning to regress the parameters of SMPL-X directly from images is challenging without paired images and 3D ground truth. Consequently, we follow the approach of SMPLify, which estimates 2D features and then optimizes model parameters to fit the features. We improve on SMPLify in several significant ways: (1) we detect 2D features corresponding to the face, hands, and feet and fit the full SMPL-X model to these; (2) we train a new neural network pose prior using a large MoCap dataset; (3) we define a new interpenetration penalty that is both fast and accurate; (4) we automatically detect gender and the appropriate body models (male, female, or neutral); (5) our PyTorch implementation achieves a speedup of more than 8x over Chumpy. We use the new method, SMPLify-X, to fit SMPL-X to both controlled images and images in the wild. We evaluate 3D accuracy on a new curated dataset comprising 100 images with pseudo ground-truth. This is a step towards automatic expressive human capture from monocular RGB data. The models, code, and data are available for research purposes at https://smpl-x.is.tue.mpg.de.

# [Dense 3D Face Decoding Over 2500FPS: Joint Texture & Shape Convolutional Mesh Decoders](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhou_Dense_3D_Face_Decoding_Over_2500FPS_Joint_Texture__Shape_CVPR_2019_paper.html)
> [Yuxiang Zhou](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Jiankang Deng](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Irene Kotsia](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Stefanos Zafeiriou](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_Dense_3D_Face_Decoding_Over_2500FPS_Joint_Texture__Shape_CVPR_2019_paper.pdf)

> 3D Morphable Models (3DMMs) are statistical models that represent facial texture and shape variations using a set of linear bases and more particular Principal Component Analysis (PCA). 3DMMs were used as statistical priors for reconstructing 3D faces from images by solving non-linear least square optimization problems. Recently, 3DMMs were used as generative models for training non-linear mappings (i.e., regressors) from image to the parameters of the models via Deep Convolutional Neural Networks (DCNNs). Nevertheless, all of the above methods use either fully connected layers or 2D convolutions on parametric unwrapped UV spaces leading to large networks with many parameters. In this paper, we present the first, to the best of our knowledge, non-linear 3DMMs by learning joint texture and shape auto-encoders using direct mesh convolutions. We demonstrate how these auto-encoders can be used to train very light-weight models that perform Coloured Mesh Decoding (CMD) in-the-wild at a speed of over 2500 FPS.

# [Monocular Total Capture: Posing Face, Body, and Hands in the Wild](http://openaccess.thecvf.com/content_CVPR_2019/html/Xiang_Monocular_Total_Capture_Posing_Face_Body_and_Hands_in_the_CVPR_2019_paper.html)
> [Donglai Xiang](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Hanbyul Joo](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Yaser Sheikh](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Xiang_Monocular_Total_Capture_Posing_Face_Body_and_Hands_in_the_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Xiang_Monocular_Total_Capture_CVPR_2019_supplemental.pdf)

> We present the first method to capture the 3D total motion of a target person from a monocular view input. Given an image or a monocular video, our method reconstructs the motion from body, face, and fingers represented by a 3D deformable mesh model. We use an efficient representation called 3D Part Orientation Fields (POFs), to encode the 3D orientations of all body parts in the common 2D image space. POFs are predicted by a Fully Convolutional Network, along with the joint confidence maps. To train our network, we collect a new 3D human motion dataset capturing diverse total body motion of 40 subjects in a multiview system. We leverage a 3D deformable human model to reconstruct total body pose from the CNN outputs with the aid of the pose and shape prior in the model. We also present a texture-based tracking method to obtain temporally coherent motion capture output. We perform thorough quantitative evaluations including comparison with the existing body-specific and hand-specific methods, and performance analysis on camera viewpoint and human pose changes. Finally, we demonstrate the results of our total body motion capture on various challenging in-the-wild videos.

# [FML: Face Model Learning From Videos](http://openaccess.thecvf.com/content_CVPR_2019/html/Tewari_FML_Face_Model_Learning_From_Videos_CVPR_2019_paper.html)
> [Ayush Tewari](http://openaccess.thecvf.com/CVPR2019_search.py%2523), [Florian Bernard](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Pablo Garrido](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Gaurav Bharaj](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Mohamed Elgharib](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Hans-Peter Seidel](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Patrick Perez](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Michael Zollhofer](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Christian Theobalt](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tewari_FML_Face_Model_Learning_From_Videos_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Tewari_FML_Face_Model_CVPR_2019_supplemental.pdf)

> Monocular image-based 3D reconstruction of faces is a long-standing problem in computer vision. Since image data is a 2D projection of a 3D face, the resulting depth ambiguity makes the problem ill-posed. Most existing methods rely on data-driven priors that are built from limited 3D face scans. In contrast, we propose multi-frame video-based self-supervised training of a deep network that (i) learns a face identity model both in shape and appearance while (ii) jointly learning to reconstruct 3D faces. Our face model is learned using only corpora of in-the-wild video clips collected from the Internet. This virtually endless source of training data enables learning of a highly general 3D face model. In order to achieve this, we propose a novel multi-frame consistency loss that ensures consistent shape and appearance across multiple frames of a subject's face, thus minimizing depth ambiguity. At test time we can use an arbitrary number of frames, so that we can perform both monocular as well as multi-frame reconstruction.

# [High-Quality Face Capture Using Anatomical Muscles](http://openaccess.thecvf.com/content_CVPR_2019/html/Bao_High-Quality_Face_Capture_Using_Anatomical_Muscles_CVPR_2019_paper.html)
> [Michael Bao](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Matthew Cong](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Stephane Grabli](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Ronald Fedkiw](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Bao_High-Quality_Face_Capture_Using_Anatomical_Muscles_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Bao_High-Quality_Face_Capture_CVPR_2019_supplemental.pdf)

> Muscle-based systems have the potential to provide both anatomical accuracy and semantic interpretability as compared to blendshape models; however, a lack of expressivity and differentiability has limited their impact. Thus, we propose modifying a recently developed rather expressive muscle-based system in order to make it fully-differentiable; in fact, our proposed modifications allow this physically robust and anatomically accurate muscle model to conveniently be driven by an underlying blendshape basis. Our formulation is intuitive, natural, as well as monolithically and fully coupled such that one can differentiate the model from end to end, which makes it viable for both optimization and learning-based approaches for a variety of applications. We illustrate this with a number of examples including both shape matching of three-dimensional geometry as as well as the automatic determination of a three-dimensional facial pose from a single two-dimensional RGB image without using markers or depth information.

# [Towards High-Fidelity Nonlinear 3D Face Morphable Model](http://openaccess.thecvf.com/content_CVPR_2019/html/Tran_Towards_High-Fidelity_Nonlinear_3D_Face_Morphable_Model_CVPR_2019_paper.html)
> [Luan Tran](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Feng Liu](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Xiaoming Liu](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Tran_Towards_High-Fidelity_Nonlinear_3D_Face_Morphable_Model_CVPR_2019_paper.pdf)

> Embedding 3D morphable basis functions into deep neural networks opens great potential for models with better representation power. However, to faithfully learn those models from an image collection, it requires strong regularization to overcome ambiguities involved in the learning process. This critically prevents us from learning high fidelity face models which are needed to represent face images in high level of details. To address this problem, this paper presents a novel approach to learn additional proxies as means to side-step strong regularizations, as well as, leverages to promote detailed shape/albedo. To ease the learning, we also propose to use a dual-pathway network, a carefully-designed architecture that brings a balance between global and local-based models. By improving the nonlinear 3D morphable model in both learning objective and network architecture, we present a model which is superior in capturing higher level of details than the linear or its precedent nonlinear counterparts. As a result, our model achieves state-of-the-art performance on 3D face reconstruction by solely optimizing latent representations.

# [Learning to Regress 3D Face Shape and Expression From an Image Without 3D Supervision](http://openaccess.thecvf.com/content_CVPR_2019/html/Sanyal_Learning_to_Regress_3D_Face_Shape_and_Expression_From_an_CVPR_2019_paper.html)
> [Soubhik Sanyal](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Timo Bolkart](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Haiwen Feng](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Michael J. Black](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Sanyal_Learning_to_Regress_3D_Face_Shape_and_Expression_From_an_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Sanyal_Learning_to_Regress_CVPR_2019_supplemental.zip)

> The estimation of 3D face shape from a single image must be robust to variations in lighting, head pose, expression, facial hair, makeup, and occlusions. Robustness requires a large training set of in-the-wild images, which by construction, lack ground truth 3D shape. To train a network without any 2D-to-3D supervision, we present RingNet, which learns to compute 3D face shape from a single image. Our key observation is that an individual's face shape is constant across images, regardless of expression, pose, lighting, etc. RingNet leverages multiple images of a person and automatically detected 2D face features. It uses a novel loss that encourages the face shape to be similar when the identity is the same and different for different people. We achieve invariance to expression by representing the face using the FLAME model. Once trained, our method takes a single image and outputs the parameters of FLAME, which can be readily animated. Additionally we create a new database of faces "not quite in-the-wild" (NoW) with 3D head scans and high-resolution images of the subjects in a wide variety of conditions. We evaluate publicly available methods and find that RingNet is more accurate than methods that use 3D supervision. The dataset, model, and results are available for research purposes at http://ringnet.is.tuebingen.mpg.de.

# [Self-Supervised Adaptation of High-Fidelity Face Models for Monocular Performance Tracking](http://openaccess.thecvf.com/content_CVPR_2019/html/Yoon_Self-Supervised_Adaptation_of_High-Fidelity_Face_Models_for_Monocular_Performance_Tracking_CVPR_2019_paper.html)
> [Jae Shin Yoon](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Takaaki Shiratori](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Shoou-I Yu](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Hyun Soo Park](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yoon_Self-Supervised_Adaptation_of_High-Fidelity_Face_Models_for_Monocular_Performance_Tracking_CVPR_2019_paper.pdf), [supp](http://openaccess.thecvf.com/content_CVPR_2019/supplemental/Yoon_Self-Supervised_Adaptation_of_CVPR_2019_supplemental.pdf)

> Improvements in data-capture and face modeling techniques have enabled us to create high-fidelity realistic face models. However, driving these realistic face models requires special input data, e.g., 3D meshes and unwrapped textures. Also, these face models expect clean input data taken under controlled lab environments, which is very different from data collected in the wild. All these constraints make it challenging to use the high-fidelity models in tracking for commodity cameras. In this paper, we propose a self-supervised domain adaptation approach to enable the animation of high-fidelity face models from a commodity camera. Our approach first circumvents the requirement for special input data by training a new network that can directly drive a face model just from a single 2D image. Then, we overcome the domain mismatch between lab and uncontrolled environments by performing self-supervised domain adaptation based on "consecutive frame texture consistency" based on the assumption that the appearance of the face is consistent over consecutive frames, avoiding the necessity of modeling the new environment such as lighting or background. Experiments show that we are able to drive a high-fidelity face model to perform complex facial motion from a cellphone camera without requiring any labeled data from the new domain.

# [Speech2Face: Learning the Face Behind a Voice](http://openaccess.thecvf.com/content_CVPR_2019/html/Oh_Speech2Face_Learning_the_Face_Behind_a_Voice_CVPR_2019_paper.html)
> [Tae-Hyun Oh](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Tali Dekel](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Changil Kim](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Inbar Mosseri](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[William T. Freeman](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Michael Rubinstein](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Wojciech Matusik](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Oh_Speech2Face_Learning_the_Face_Behind_a_Voice_CVPR_2019_paper.pdf)

> How much can we infer about a person's looks from the way they speak? In this paper, we study the task of reconstructing a facial image of a person from a short audio recording of that person speaking. We design and train a deep neural network to perform this task using millions of natural Internet/Youtube videos of people speaking. During training, our model learns voice-face correlations that allow it to produce images that capture various physical attributes of the speakers such as age, gender and ethnicity. This is done in a self-supervised manner, by utilizing the natural co-occurrence of faces and speech in Internet videos, without the need to model attributes explicitly. We evaluate and numerically quantify how--and in what manner--our Speech2Face reconstructions, obtained directly from audio, resemble the true face images of the speakers.

# [Boosting Local Shape Matching for Dense 3D Face Correspondence](http://openaccess.thecvf.com/content_CVPR_2019/html/Fan_Boosting_Local_Shape_Matching_for_Dense_3D_Face_Correspondence_CVPR_2019_paper.html)
> [Zhenfeng Fan](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Xiyuan Hu](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Chen Chen](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Silong Peng](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Fan_Boosting_Local_Shape_Matching_for_Dense_3D_Face_Correspondence_CVPR_2019_paper.pdf)

> Dense 3D face correspondence is a fundamental and challenging issue in the literature of 3D face analysis. Correspondence between two 3D faces can be viewed as a non-rigid registration problem that one deforms into the other, which is commonly guided by a few facial landmarks in many existing works. However, the current works seldom consider the problem of incoherent deformation caused by landmarks. In this paper, we explicitly formulate the deformation as locally rigid motions guided by some seed points, and the formulated deformation satisfies coherent local motions everywhere on a face. The seed points are initialized by a few landmarks, and are then augmented to boost shape matching between the template and the target face step by step, to finally achieve dense correspondence. In each step, we employ a hierarchical scheme for local shape registration, together with a Gaussian reweighting strategy for accurate matching of local features around the seed points. In our experiments, we evaluate the proposed method extensively on several datasets, including two publicly available ones: FRGC v2.0 and BU-3DFE. The experimental results demonstrate that our method can achieve accurate feature correspondence, coherent local shape motion, and compact data representation. These merits actually settle some important issues for practical applications, such as expressions, noise, and partial data.

# [Combining 3D Morphable Models: A Large Scale Face-And-Head Model](http://openaccess.thecvf.com/content_CVPR_2019/html/Ploumpis_Combining_3D_Morphable_Models_A_Large_Scale_Face-And-Head_Model_CVPR_2019_paper.html)
> [Stylianos Ploumpis](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Haoyang Wang](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Nick Pears](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[William A. P. Smith](http://openaccess.thecvf.com/CVPR2019_search.py%2523),[Stefanos Zafeiriou](http://openaccess.thecvf.com/CVPR2019_search.py%2523)

> [pdf](http://openaccess.thecvf.com/content_CVPR_2019/papers/Ploumpis_Combining_3D_Morphable_Models_A_Large_Scale_Face-And-Head_Model_CVPR_2019_paper.pdf)

> Three-dimensional Morphable Models (3DMMs) are powerful statistical tools for representing the 3D surfaces of an object class. In this context, we identify an interesting question that has previously not received research attention: is it possible to combine two or more 3DMMs that (a) are built using different templates that perhaps only partly overlap, (b) have different representation capabilities and (c) are built from different datasets that may not be publicly-available? In answering this question, we make two contributions. First, we propose two methods for solving this problem: i. use a regressor to complete missing parts of one model using the other, ii. use the Gaussian Process framework to blend covariance matrices from multiple models. Second, as an example application of our approach, we build a new head and face model that combines the variability and facial detail of the LSFM with the full head modelling of the LYHM. The resulting combined model achieves state-of-the-art performance and outperforms existing head models by a large margin. Finally, as an application experiment, we reconstruct full head representations from single, unconstrained images by utilizing our proposed large-scale model in conjunction with the Face-Warehouse blendshapes for handling expressions.
