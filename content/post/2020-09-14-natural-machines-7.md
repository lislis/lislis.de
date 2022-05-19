+++
title = "Natural Machines pt 7"
date = 2020-09-14
draft = false
[taxonomies]
tags = ["schoolofma", ""]
category = ["blog"]
+++

https://github.com/lawreka/aiArtAULA2020
https://ml4a.github.io/guides/
https://aiartists.org/ai-generated-art-tools

https://kathrynisabelle.com/loaf-ai


## Style Transfer
https://www.tensorflow.org/tutorials/generative/style_transfer
https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/generative/style_transfer.ipynb#scrollTo=eqxUicSPUOP6

Image classificatoins networks are practical for this, too!

What layer do you take the style from?
Lower layer -> more detail
higher layer -> more style


Keras -> abstraktion layer library for tensor flow


## DeepDream


## DCGAN


Adverserial Attack

1 Pixel attack

Dawn Sung Paper Google translate

## Autodecoder

remove encoder and feed random to generate faces etc
but very blurry
generates close to gemetry and not original ocncept

## GAN

Game Theory

Agents with different motivations

Not network tries to trick the second network (generator)
the second network tries to figure out if its being tricked (disciminator)

Autoencoder chpped and put togehter backwards

They need to be in balance, they have to learn at thesam etime


Once they are done learning, the gernator can just go and genate stuff, it never saw the original data

Latent space is a multidimensional list of all possible outputs

Optimizing to get the best possible coordinate

But its trained normally on normal distribution

What if it tries to only generate on e image but very well?
Find optimumm in local error???



https://ocw.mit.edu/resources/res-9-003-brains-minds-and-machines-summer-course-summer-2015/unit-2.-modeling-human-cognition/

https://github.com/NVlabs/SPADE


## Pix to pix

Semantic label maps (A) to realistic looking image (B)

generator generates a mapping from A to B
Diskriminator checks if for a given A the genrated B is real or not

## CycleGAN


Sample data size? 1/ 10 of what they use in the paper will give a good enough training set

Style transfer, style transfer and diskriminate against



## DAIN


Infer depth maps in images




## ML in JS and other

https://ml5js.org/

https://magenta.tensorflow.org/

https://trackingjs.com/

https://www.tensorflow.org/js


http://introtodeeplearning.com/

## Pad

STYLE GAN 2 demo
https://colab.research.google.com/drive/1ZmRLFVaMwZA4f0h12sliFdy-BYd4idPw#scrollTo=q8VnyjDhiBQY


https://pad.riseup.net/p/SchoolofMa


RUNWAY ML and Paperspace


.pkl files



pip install image-resizer
pip install instagram-scraper
