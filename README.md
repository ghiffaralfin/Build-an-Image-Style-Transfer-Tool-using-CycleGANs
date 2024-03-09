# Build an Image Style Transfer Tool using CycleGANs

Author : Sina Nazeri

Source : [CognitiveClass.ai](https://cognitiveclass.ai/courses/course-v1:IBM+GPXX0KSEEN+v1?authuser=0 "Build an Image Style Transfer Tool using CycleGANs")

---

Mentee assignment from IBM Advance AI @ Infinite Learning Course completion of Build an Image Style Transfer Tool using CycleGANs guided project from CognitiveClass.ai

<p style="text-align:center">
    <img src="https://pbs.twimg.com/media/FjJyBVrXEAIUKXX?format=jpg&name=large" width="500" alt="AI meme"  />
    </a>
</p>

---



## Mentee Info:


| Name :| Ghiffar ALfin Faiz |
|--------|--------------------|
| Program : | IBM Advanced AI |

<br>

---

## Project Info

CycleGAN is a deep learning framework designed for image-to-image translation tasks without the need for paired training data. Introduced in 2017 by Jun-Yan Zhu et al., CycleGAN operates on unpaired datasets, making it versatile for various applications such as style transfer, season conversion, and object transfiguration. At its core, CycleGAN employs two main components: generators and discriminators. The generators aim to transform images from one domain to another, while the discriminators are trained to distinguish between real and generated images. 

What sets CycleGAN apart is its integration of the cycle-consistency principle. This principle ensures that the translated images maintain important visual characteristics by enforcing that the reconstructed image after a round-trip through both generators remains similar to the original input. Through adversarial training and cycle-consistency loss minimization, CycleGAN learns to perform accurate and consistent image translations, offering a powerful solution for a wide range of image transformation tasks in an unsupervised manner.

GAN (Generative Adversarial Network) and CycleGAN are both deep learning frameworks used for image generation and transformation, but they differ in their objectives and methodologies.

GAN:

- GAN is primarily focused on generating realistic images from random noise.
- It consists of two networks: a generator and a discriminator.
- The generator generates fake images to try and fool the discriminator, which is trained to distinguish between real and fake images.
- GANs require paired training data for supervised learning, where each input image has a corresponding target image.

CycleGAN:

- CycleGAN is designed for image-to-image translation tasks without paired training data.
- It employs two generators and two discriminators.
- The generators aim to translate images from one domain to another, while the discriminators assess the authenticity of the translated images.
- CycleGAN introduces the concept of cycle-consistency loss, ensuring that the translated images maintain important visual characteristics by enforcing consistency between the original and translated images.
- It can be applied to tasks such as style transfer, season conversion, and object transfiguration.

In summary, while both GAN and CycleGAN are used for image generation and transformation, GAN focuses on generating realistic images from noise with paired training data, whereas CycleGAN specializes in image-to-image translation tasks without requiring paired training data, utilizing cycle-consistency to ensure accurate and consistent transformations.




<p style="font-size:40px; text-align:center">Thank you</p>
