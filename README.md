# Generative Adversarial Networks (GAN)

by Uki D. Lucas, the project was started in December 2020 on [GitHub](https://github.com/UkiDLucas/GAN)



In this study, I attempt to explain the Generative Adversarial Networks (GAN), arguably the **most formidable force in currently available compute science**.



## Analogy in biology



The life on Earth is defined by competition of organisms. At any place and time, there is a set of conditions that represent a present "state-of-the-art". 

Imagine the primordial savanna. There are the top predators, the nimblest of the antelopes, the best camouflage users, and maybe, there are some fire-making apes, the smartest of the bunch. These are the current incumbents, the best in each in their own speciality. 

And then, there are challengers, the newcomers that are slightly different, hoping to gain an extra edge to win in the never ending race.

The challengers always try to outcompete the incumbents, often this happens by a better design, and sometimes because the conditions have changed favoring a new design.



### In Computer Science



In computer science, we train one "model" on what is considered the current state-of-the-art, it is often called the "**discriminator**" model.

Then, we create another model capable of imagining zillions of new designs, it is called the "**generator**" model.

The nomenclature being currently used, such as discriminator, generator, adversarial networks and the game theory are rather heavy footed and it is more appropriate for the Darwinian evolution where the looser becomes the lunch menu. You can also think about GAN as a interaction between  a "**mentor**" and a "**student**". I will use it as it is easier for the reader to relate to.

Every new design of the student is compared to the current state-of-the-art, the mentor provides a feedback on how well the student did. In reality, the student "generator" of the new design is nothing but a combination of millions of parameters seeking an optimal solution. Based on the feedback from the mentor, the student adjusts the parameters. The adjustment can be large if the creation was totally off, or it can be very small if the creation is almost perfect. 

When the new design is better, or at least indistinguishable in quality, the new standard is adopted. Yes, the mentor model can learn as well.

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
- [YouTube: Jeff Heaton: Create High Resolution GAN Faces with Pretrained NVidia StyleGAN and Google CoLab](https://www.youtube.com/watch?v=RPGOPrkieTE&list=PLjy4p-07OYzs6XDEm39m6g7yZWXB6MKac)

