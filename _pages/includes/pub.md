
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing</div><img src='images/Neurocomputing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Sonar Image Garbage Detection via Global Despeckling and Dynamic Attention Graph Optimization](https://www.sciencedirect.com/science/article/pii/S0925231223001133)<br>
Keyang Cheng, Liuyang Yan, Yi Ding, **<font style="background: #eeffee">Hao Zhou</font>**, Maozhen Li, Humaira abdul Ghafoor.<br>
<span style="color:#9A2617;">Neurocomputing</span><br>
<div style="height:150px;width:auto;overflow:auto;background-color:#def;scrollbar-base-color:gold;font-family:sans-serif;font-size:12px;padding:10px;overflow:auto;border:1px solid #abf;"><strong>Abstract</strong><br>
Sonar is widely used in marine water cleaning tasks, so sonar images have become an effective tool for garbage detection and underwater scene analysis. However, it is an extremely difficult task to achieve fully supervised denoising and garbage detection for sonar images. This is because sonar images are weakly annotated samples that are susceptible to noise interference and have no reference clean image. To this end, we propose a sonar image garbage instance segmentation model via global despeckling and dynamic attention graph optimization(GD-DAGO). Specifically, a self-supervised blind spot network denoising structure is presented in this paper. The proposed denoising model overcomes the defects of information loss in the traditional blind spot network structure and performs global awareness speckle suppression for the noise characteristics of sonar images themselves. In addition, a novel dynamic attention structure is employed to improve the target region estimation in the instance segmentation module and does not require supervision beyond image-level category labeling. Finally, in order to enhance the cooperative ability between the two tasks, we adopt a local perceptual loss strategy based on mask proposals guided by the downstream task, so that the whole model takes more into account the characteristics of sonar images and better serves the sonar garbage detection task. Experimental results on ARACATI 2017 and marine-debris-fls-datasets (MDFD) show that the proposed algorithm achieves a performance gain of 0.4218 and 4.2% in terms of denoising effect (ENL) and detection accuracy (AP25), respectively, compared with suboptimal algorithms.
</div><br>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMVC 2022</div><img src='images/IBSG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Improving Interpretability by Information Bottleneck Saliency Guided Localization](https://bmvc2022.mpi-inf.mpg.de/605/)<br>
**<font style="background: #eeffee">Hao Zhou</font>**, Keyang Cheng, Yu Si, Liuyang Yan<br>
<span style="color:#9A2617;">British Machine Vision Conference (BMVC) 2022</span><br>
<div style="height:150px;width:auto;overflow:auto;background-color:#def;scrollbar-base-color:gold;font-family:sans-serif;font-size:12px;padding:10px;overflow:auto;border:1px solid #abf;"><strong>Abstract</strong><br>
The saliency map produced by current deep neural network models fails to accurately focus on important regions of an image due to the influence of input noise. In this paper, we propose a deep learning interpretability method based on information bottleneck, which guides the model training by the probability distribution between the saliency map attributed by the information bottleneck and the gradient-based saliency map. This approach corrects the important regions focused by the model from an information-theoretic perspective. Meanwhile, a saliency suppression mechanism is presented to keep the saliency map of the model away from incorrect classification results and close to correct ones. Experiments show that our method can improve the saliency localization of the model while retaining its accuracy. Compared with other state-of-the-art methods, the Average Drop rate improves by 1.57% and 1.43%, and the Average Increase rate improves by 2.18% and 0.18% in the ResNet-50 model and the VGG-16 model, respectively.
</div><br>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/MMDV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MMDV: Interpreting DNNs via Building Evaluation Metrics, Manual Manipulation and Decision Visualization](https://dl.acm.org/doi/abs/10.1145/3503161.3548260)<br>
Keyang Cheng, Yu Si, **<font style="background: #eeffee">Hao Zhou</font>**, Rabia Tahir<br>
<span style="color:#9A2617;">ACM International Conference on Multimedia (ACM MM) 2022</span><br>
<div style="height:150px;width:auto;overflow:auto;background-color:#def;scrollbar-base-color:gold;font-family:sans-serif;font-size:12px;padding:10px;overflow:auto;border:1px solid #abf;"><strong>Abstract</strong><br>
The unexplainability and untrustworthiness of deep neural networks hinder their application in various high-risk fields. The existing methods lack solid evaluation metrics, interpretable models, and controllable manual manipulation. This paper presents Manual Manipulation and Decision Visualization (MMDV) which makes Human-in-the-loop improve the interpretability of deep neural networks. The MMDV offers three unique benefits: 1) The Expert-drawn CAM (Draw CAM) is presented to manipulate the key feature map and update the convolutional layer parameters, which makes the model focus on and learn the important parts by making a mask of the input image from the CAM drawn by the expert; 2) A hierarchical learning structure with sequential decision trees is proposed to provide a decision path and give strong interpretability for the fully connected layer of DNNs; 3) A novel metric, Data-Model-Result interpretable evaluation(DMR metric), is proposed to assess the interpretability of data, model and the results. Comprehensive experiments are conducted on the pre-trained models and public datasets. The results of the DMR metric are 0.4943, 0.5280, 0.5445 and 0.5108. These data quantifications represent the interpretability of the model and results. The attention force ratio is about 6.5% higher than the state-of-the-art methods. The Average Drop rate achieves 26.2% and the Average Increase rate achieves 36.6%. We observed that MMDV is better than other explainable methods by attention force ratio under the positioning evaluation. Furthermore, the manual manipulation disturbance experiments show that MMDV correctly locates the most responsive region in the target item and explains the model's internal decision-making basis. The MMDV not only achieves easily understandable interpretability but also makes it possible for people to be in the loop.
</div><br>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICPCSEE 2022</div><img src='images/DRIB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[DRIB: Interpreting DNN with Dynamic Reasoning and Information Bottleneck](https://link.springer.com/chapter/10.1007/978-981-19-5194-7_14)<br>
Yu Si, Keyang Cheng, Zhou Jiang, **<font style="background: #eeffee">Hao Zhou</font>**, Rabia Tahir<br>
<span style="color:#9A2617;">International Conference of Pioneering Computer Scientists, Engineers and Educators (ICPCSEE) 2022</span><br>
<div style="height:150px;width:auto;overflow:auto;background-color:#def;scrollbar-base-color:gold;font-family:sans-serif;font-size:12px;padding:10px;overflow:auto;border:1px solid #abf;"><strong>Abstract</strong><br>
The interpretability of deep neural networks has aroused widespread concern in the academic and industrial fields. This paper proposes a new method named the dynamic reasoning and information bottleneck (DRIB) to improve human interpretability and understandability. In the method, a novel dynamic reasoning decision algorithm was proposed to reduce multiply accumulate operations and improve the interpretability of the calculation. The information bottleneck was introduced to the DRIB model to verify the attribution correctness of the dynamic reasoning module. The DRIB reduces the burden approximately 50% by decreasing the amount of computation. In addition, DRIB keeps the correct rate at approximately 93%. The information bottleneck theory verifies the effectiveness of this method, and the credibility is approximately 85%. In addition, through visual verification of this method, the highlighted area can reach 50% of the predicted area, which can be explained more obviously. Some experiments prove that the dynamic reasoning decision algorithm and information bottleneck theory can be combined with each other. Otherwise, the method provides users with good interpretability and understandability, making deep neural networks trustworthy.
</div><br>
</div>
</div>

<!-- - ``ICPCSEE 2022`` [DRIB: Interpreting DNN with Dynamic Reasoning and Information Bottleneck](https://link.springer.com/chapter/10.1007/978-981-19-5194-7_14). <br>Yu Si, Keyang Cheng, Zhou Jiang, **<font style="background: #eeffee">Hao Zhou</font>**, Rabia Tahir. -->
