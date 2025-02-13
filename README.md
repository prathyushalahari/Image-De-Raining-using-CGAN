# Image-De-Raining-using-ID-CGAN
Collaborator - Chetan Nadigar

Abstract :

Severe weather conditions such as rain and snow adversely affect the visual quality of images captured under such conditions thus rendering them useless for further usage and sharing. In addition, such degraded images drastically affect performance of vision systems. Hence, it is important to address the problem of single image de-raining. However, the inherent ill-posed nature of the problem presents several challenges. We attempt to leverage powerful generative modeling capabilities of the recently introduced Conditional Generative Adversarial Networks (CGAN) by enforcing an additional constraint that the de-rained image must be indistinguishable from its corresponding ground truth clean image. The adversarial loss from GAN provides additional regularization and helps to achieve superior results. In addition to presenting a new approach to de-rain images, we introduce a new refined loss function and architectural novelties in the generator-discriminator pair for achieving improved results. The loss function is aimed at reducing artifacts introduced by GANs and ensure better visual quality.
The generator sub-network is constructed using the recently introduced densely connected networks, whereas the discriminator is designed to leverage global and local information to decide if
an image is real/fake. Based on this, we propose a novel single image de-raining method called Image De-raining Conditional Generative Adversarial Network (ID-CGAN), which considers
quantitative, visual and also discriminative performance into the objective function. Experiments evaluated on synthetic and real images show that the proposed method outperforms many recent
state-of-the-art single image de-raining methods in terms of quantitative and visual performance. 
