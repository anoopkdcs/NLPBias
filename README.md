# Bias in Pre-trained Neural Language Models
<img src= 'img/plm_bias.png'>
** Towards Comprehensive Understanding of Bias in Pre-trained Neural Language Models: A Survey with Special Emphasis on Affective Bias ** </br>
Anoop K<sup>1</sup>, Manjary P Gangan<sup>1</sup>, Deepak P<sup>2,3</sup>  and Lajish V L<sup>1</sup> </br>
Computational Intelligence and Data Analytics (CIDA Lab) </br>
Department of Computer Science </br>
University of Calicut, India

:memo: Paper : https://arxiv.org/abs/2110.09428 </br>
:earth_asia: Link: https://dcs.uoc.ac.in/cida/projects/dif/mceffnet.html

**Abstract**: The problem of distinguishing natural images from photo-realistic computer-generated ones either addresses _natural images versus computer graphics_ or _natural images versus GAN images_, at a time. But in a real-world image forensic scenario, it is highly essential to consider all categories of image generation, since in most cases image generation is unknown. We, for the first time, to our best knowledge, approach the problem of distinguishing natural images from photo-realistic computer-generated images as a three-class classification task classifying natural, computer graphics, and GAN images. For the task, we propose a Multi-Colorspace fused EfficientNet model by parallelly fusing three EfficientNet networks that follow transfer learning methodology where each network operates in different colorspaces, RGB, LCH, and HSV, chosen after analyzing the efficacy of various colorspace transformations in this image forensics problem. Our model outperforms the baselines in terms of accuracy, robustness towards post-processing, and generalizability towards other datasets. We conduct psychophysics experiments to understand how accurately humans can distinguish natural, computer graphics, and GAN images where we could observe that humans find difficulty in classifying these images, particularly the computer-generated images, indicating the necessity of computational algorithms for the task. We also analyze the behavior of our model through visual explanations to understand salient regions that contribute to the model's decision making and compare with manual explanations provided by human participants in the form of region markings, where we could observe similarities in both the explanations indicating the powerful nature of our model to take the decisions meaningfully. 

For other inquiries, please contact: </br>
Manjary P Gangan :email: manjaryp_dcs@uoc.ac.in :earth_asia: [website](https://dcs.uoc.ac.in/~manjary/) </br>
Anoop K :email: anoopk_dcs@uoc.ac.in :earth_asia: [website](https://dcs.uoc.ac.in/~anoop/)</br>
Lajish V L :email: lajish@uoc.ac.in :earth_asia: [website](https://dcs.uoc.ac.in/index.php/dr-lajish-v-l)

## Citation
```
@misc{gangan2021distinguishing,
      title={Distinguishing Natural and Computer-Generated Images using Multi-Colorspace fused EfficientNet}, 
      author={Manjary P Gangan and Anoop K and Lajish V L},
      year={2021},
      eprint={2110.09428},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
