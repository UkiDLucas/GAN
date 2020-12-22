# Generative Adversarial Networks (GAN)

by Uki D. Lucas, started in December 2020 on [GitHub](https://github.com/UkiDLucas/GAN)



In this study, I attempt to understand, explain and showcase the Generative Adversarial Networks (GAN), arguably the most formidable force in currently available compute science.



## Explanation via analogy



The life on Earth is defined by competition of organisms. At any place and time, there is a set of conditions that represent a present "state-of-the-art". 

Imagine the primordial savanna. There are the nimblest of the antelopes, the top predators, the best of the of the camouflage users, and maybe, there are some fire-making apes, the smartest of the bunch. These are the current incumbents, the best of the best, each in their own speciality. 

And then, there are challengers, the newcomers that are slightly different, hoping to gain this extra edge to win in the never ending race.

The challengers always try to outcompete the incumbents, often this happens by a better design, and sometimes because the conditions have changed favoring a new design.



### Translation to the Computer Science



In computer science, we train one "model" on what is considered the current state-of-the-art, it is often called the "discriminator" model.

Then, we create another "model" capable of developing zillions of new designs, it is called the "generator" model.

Every new design is compared to the current state-of-the-art and if it is better, or at least indistinguishable in quality, the new standard is adopted. The "discriminator" model trains to adopt to a new level.

What's more important, the "discriminator" provides a feedback to the "generator" on how well it did. 

In reality, the "generator" factory of the new design is nothing but a combination of millions of parameters set to the optimal combination. Computer tries many combinations until it derives the optimal solution.

Based on that feedback form "discriminator", the "generator" adjusts its parameters. The adjustment can be large if the creation was totally off, or the adjustment can be very small if the creation is almost perfect. Darwinian evolution. 

In summary, the name Generative Adversarial Networks (GAN) implies that there are two or more "deep neural networks" which compete against each other via generation of new models. 





## To follow up

"In May 2019, researchers at Samsung demonstrated a GAN-based system that produces videos of a person speaking, given only a single photo of that person"





## RESOURCES

- https://en.wikipedia.org/wiki/Generative_adversarial_network
- [Ian Goodfellow: Generative Adversarial Networks (GANs) | Lex Fridman Podcast #19](https://www.youtube.com/watch?v=Z6rxFNMGdn0&t=453s)
- https://github.com/NVlabs/metfaces-dataset
- https://www.youtube.com/watch?v=BIZg_PPuj_0
- https://www.youtube.com/watch?v=kSLJriaOumA
- https://www.youtube.com/watch?v=idIHmtjz1EQ&feature=youtu.be
- https://www.theverge.com/2019/3/5/18251267/ai-art-gans-mario-klingemann-auction-sothebys-technology
- https://en.wikipedia.org/wiki/Edmond_de_Belamy 
- [Generative Adversarial Networks (GANs) - Computerphile - Rob Miles](https://www.youtube.com/watch?v=Sw9r8CL98N0)
- 

