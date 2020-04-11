# GANtastic
![](https://github.com/darthgera123/GANtastic/blob/master/results/SGAN_architecture.png)  
This repo contains my experiments with different types of GANs and different types of losses that are used. It is an attempt to fully understand and appreciate this concept which the father of CNNs, **Yann Le Cunn** has called it as the coolest idea in deep learning in the last 20 years.  

I have always been fascinated by GANs and their ability to create images which are so lifelike and real be it new faces, new types of cars or new types of interior designing. However, in this quarantine period(COVID-19), where everybody is brushing up their art skills, I thought to give mine a go. So being the artist I am, I decided it was easier for me to sit through frustrating hours of training GANs rather than my hands to generate art xD.  

Apart from that, there are several papers and blogs which I found useful. 

## Implementations
I have implemented the following architectures - 
+ SGAN - Standard Gan
+ DCGAN - Deep Convolution GAN
+ RaLSGAN - Relativistic Average on Least Square GAN
+ Cycle Gan with Least Square error.

## Results
**SGAN on MNIST**
<p >
  <img src="https://github.com/darthgera123/GANtastic/blob/master/results/SGAN_result.png" width="600" height="400" />
</p>  

**RaLSGAN on Dogs Dataset**
<p >
  <img src="https://github.com/darthgera123/GANtastic/blob/master/results/Improved_RaLSGAN.png" width="600" height="600" />
</p>

**Mode Collapse on Dogs Dataset**
(although i shouldnt be showing this off)

## Resources
+ [Original GAN paper](https://arxiv.org/pdf/1406.2661.pdf)
+ [DCGAN or Deep Convolutional GAN](https://arxiv.org/pdf/1511.06434.pdf) 
+ https://pathmind.com/wiki/generative-adversarial-network-gan
+ https://machinelearningmastery.com/resources-for-getting-started-with-generative-adversarial-networks/
+ https://medium.com/ai-society/gans-from-scratch-1-a-deep-introduction-with-code-in-pytorch-and-tensorflow-cb03cdcdba0f
+ [Tips and Tricks while training](https://github.com/soumith/ganhacks)
+ [Deep Mind slides](http://www.gatsby.ucl.ac.uk/~balaji/Understanding-GANs.pdf)
+ [Advanced Tricks](https://towardsdatascience.com/10-lessons-i-learned-training-generative-adversarial-networks-gans-for-a-year-c9071159628)
+ [RaLS Resource](https://www.kaggle.com/c/generative-dog-images/discussion/99485)
+ [GAN awesome applications repo](https://github.com/nashory/gans-awesome-applications)
+ [DCGAN for art](https://www.ritchievink.com/blog/2018/07/16/generative-adversarial-networks-in-pytorch-the-distribution-of-art/)
+ [GANs implemented Pytorch](https://github.com/ozanciga/gans-with-pytorch)
+ [GAN to WGAN](https://lilianweng.github.io/lil-log/2017/08/20/from-GAN-to-WGAN.html)
+ [Interesting GAN application 2019](https://heartbeat.fritz.ai/artificial-art-how-gans-are-making-machines-creative-b99105627198)

## Datasets
+ [Dog Dataset](https://www.kaggle.com/c/generative-dog-images/data)

## Notes
+ The dog dataset has images of the size 64x64x3 hence they may be difficult to look at.
