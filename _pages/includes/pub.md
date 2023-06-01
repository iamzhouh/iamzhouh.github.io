
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BMVC 2022</div><img src='images/IBSG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Improving Interpretability by Information Bottleneck Saliency Guided Localization](https://bmvc2022.mpi-inf.mpg.de/605/)\\
**<font style="background: #eeffee">Hao Zhou</font>**, Keyang Cheng, Yu Si, Liuyang Yan\\
  
<div style="height:100px;width:auto;overflow:auto;background-color:#def;scrollbar-base-color:gold;font-family:sans-serif;font-size:15px;padding:10px;overflow:auto;border:1px solid #abf;"><strong>Abstract</strong><br>
The saliency map produced by current deep neural network models fails to accurately focus on important regions of an image due to the influence of input noise. In this paper, we propose a deep learning interpretability method based on information bottleneck, which guides the model training by the probability distribution between the saliency map attributed by the information bottleneck and the gradient-based saliency map. This approach corrects the important regions focused by the model from an information-theoretic perspective. Meanwhile, a saliency suppression mechanism is presented to keep the saliency map of the model away from incorrect classification results and close to correct ones. Experiments show that our method can improve the saliency localization of the model while retaining its accuracy. Compared with other state-of-the-art methods, the Average Drop rate improves by 1.57% and 1.43%, and the Average Increase rate improves by 2.18% and 0.18% in the ResNet-50 model and the VGG-16 model, respectively.
</div>
  
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/MMDV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MMDV: Interpreting DNNs via Building Evaluation Metrics, Manual Manipulation and Decision Visualization](https://dl.acm.org/doi/abs/10.1145/3503161.3548260)\\
Keyang Cheng, Yu Si, **<font style="background: #eeffee">Hao Zhou</font>**, Rabia Tahir\\
  
<div style="height:100px;width:auto;overflow:auto;background-color:#def;scrollbar-base-color:gold;font-family:sans-serif;font-size:15px;padding:10px;overflow:auto;border:1px solid #abf;"><strong>Abstract</strong><br>
The unexplainability and untrustworthiness of deep neural networks hinder their application in various high-risk fields. The existing methods lack solid evaluation metrics, interpretable models, and controllable manual manipulation. This paper presents Manual Manipulation and Decision Visualization (MMDV) which makes Human-in-the-loop improve the interpretability of deep neural networks. The MMDV offers three unique benefits: 1) The Expert-drawn CAM (Draw CAM) is presented to manipulate the key feature map and update the convolutional layer parameters, which makes the model focus on and learn the important parts by making a mask of the input image from the CAM drawn by the expert; 2) A hierarchical learning structure with sequential decision trees is proposed to provide a decision path and give strong interpretability for the fully connected layer of DNNs; 3) A novel metric, Data-Model-Result interpretable evaluation(DMR metric), is proposed to assess the interpretability of data, model and the results. Comprehensive experiments are conducted on the pre-trained models and public datasets. The results of the DMR metric are 0.4943, 0.5280, 0.5445 and 0.5108. These data quantifications represent the interpretability of the model and results. The attention force ratio is about 6.5% higher than the state-of-the-art methods. The Average Drop rate achieves 26.2% and the Average Increase rate achieves 36.6%. We observed that MMDV is better than other explainable methods by attention force ratio under the positioning evaluation. Furthermore, the manual manipulation disturbance experiments show that MMDV correctly locates the most responsive region in the target item and explains the model's internal decision-making basis. The MMDV not only achieves easily understandable interpretability but also makes it possible for people to be in the loop.
</div>

</div>
</div>

- ``Neurocomputing`` [Sonar Image Garbage Detection via Global Despeckling and Dynamic Attention Graph Optimization](https://www.sciencedirect.com/science/article/pii/S0925231223001133). \\Keyang Cheng, Liuyang Yan, Yi Ding, **<font style="background: #eeffee">Hao Zhou</font>**, Maozhen Li and Humaira abdul Ghafoor.
- ``ICPCSEE 2022`` [DRIB: Interpreting DNN with Dynamic Reasoning and Information Bottleneck](https://link.springer.com/chapter/10.1007/978-981-19-5194-7_14). \\Yu Si, Keyang Cheng, Zhou Jiang, **<font style="background: #eeffee">Hao Zhou</font>** and Rabia Tahir.
