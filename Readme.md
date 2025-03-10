# GenerativeAdversarial Networks for High-Resolution Image Enhancement
##### Deep Learning course, "Mention SDI"
##### Alexandre Boistard

This project studies how to enhance low-resolution images into high-resolution counterparts using **Generative Adversarial Networks (GANs)**. The **Super-Resolution Generative Adversarial Network (SRGAN)** was a pioneering Deep Learning approach that combined GANs with perceptual loss, enabling the generation of sharper and more realistic images. Despite its success, SRGAN struggled with recovering fine textures and often introduced artifacts in challenging scenarios.

Building upon this, the **Enhanced Super-Resolution Generative Adversarial Network (ESRGAN)** improved image quality significantly by replacing SRGAN’s original building blocks with **Residual-in-Residual Dense Blocks (RRDBs)**. ESRGAN introduced new “basic blocs” as well as a **Relativistic GAN**, enhancing the discriminator’s ability to evaluate realism between real and generated images.

Studying the transition from SRGAN to ESRGAN allows for a better understanding of the motivations behind using this model. This project also aims to highlight some limitations of ESRGAN in practice, which justify the need for further research, broader training, and the introduction of other architectures.