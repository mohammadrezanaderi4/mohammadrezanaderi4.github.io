---
image: '/Projects_image/pic05.jpg'
title: "Dynamic-Pix2Pix: Medical image segmentation by injecting noise to cGAN for modeling input and target domain joint distributions with limited training data"
collection: publications
category: manuscripts
permalink: /publication/2024-03-19-content-aware-image-retargeting
excerpt: '<br /><br /><br /><br /><br />'
date: 2023-10-01
venue: 'Biomedical Signal Processing and Control'
slidesurl: 'https://arxiv.org/pdf/2211.08570'
paperurl: 'https://doi.org/10.1016/j.bspc.2023.104877'
citation: 'Naderi, Mohammad Reza, Karimi, N., Emami, A., Shirani, S. & Samavi, S. Dynamic-Pix2Pix:
Medical image segmentation by injecting noise to cGAN for modeling input and target domain joint distributions with limited training data. Biomedical Signal Processing and Control 85. (2023)'
---

Learning to translate images from a source to a target domain with applications such as converting simple line drawing to oil painting has attracted significant attention. The quality of translated images is directly related to two crucial issues. First, the consistency of the output distribution with that of the target is essential. Second, the generated output should have a high correlation with the input. Conditional Generative Adversarial Networks, cGANs, are the most common models for translating images. The performance of a cGAN drops when we use a limited training dataset. In this work, we study the obstacles that prevent a U-shaped model from learning the target domain distribution from limited data by using noise as input. This study helps to increase the Pix2Pix (a form of cGAN) target distribution modeling ability from limited data with the help of dynamic neural network theory. Our model has two learning cycles. The model learns the correlation between input and ground truth in the first cycle. Then, the model's architecture is refined in the second cycle to learn the target distribution from noise input. These processes are executed in each iteration of the training procedure. Helping the cGAN learn the target distribution from noise input results in a better model generalization during the test time and allows the model to fit almost perfectly to the target domain distribution. As a result, our model surpasses the Pix2Pix model in segmenting HC18 and Montgomery's chest x-ray images. Both qualitative and Dice scores show the superiority of our model. Although our proposed method does not use thousand of additional data for pretraining, it produces comparable results for the in and out-domain generalization compared to the state-of-the-art methods.
