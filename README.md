# Litterature

## GAN background
- **Goodfellow, Ian, et al. "Generative adversarial nets." Advances in neural information processing systems. 2014.**
- Salimans, Tim, et al. "Improved techniques for training gans." Advances in Neural Information Processing Systems. 2016.
- Arjovsky, Martin, Soumith Chintala, and Léon Bottou. "Wasserstein gan." arXiv preprint arXiv:1701.07875 (2017).
- **Mirza, Mehdi, and Simon Osindero. "Conditional generative adversarial nets." arXiv preprint arXiv:1411.1784 (2014).**
- **Lucic, Mario, et al. "Are GANs Created Equal? A Large-Scale Study." arXiv preprint arXiv:1711.10337 (2017).**

## Image-to-image models
 - **Isola, Phillip, et al. "Image-to-image translation with conditional adversarial networks." arXiv preprint arXiv:1611.07004 (2016).**
 - Zhu, Jun-Yan, et al. "Unpaired image-to-image translation using cycle-consistent adversarial networks." arXiv preprint arXiv:1703.10593 (2017).
 - Shrivastava, Ashish, et al. "Learning from simulated and unsupervised images through adversarial training." arXiv preprint arXiv:1612.07828 (2016).
 - Zhu, Jun-Yan, et al. "Toward Multimodal Image-to-Image Translation." arXiv preprint arXiv:1711.11586 (2017).

## Interesting ideas
- **Triple GAN: https://papers.nips.cc/paper/6997-triple-generative-adversarial-nets.**
- Similar: Gan, Zhe, et al. "Triangle generative adversarial networks." Advances in Neural Information Processing Systems. 2017.

## Promising results
- Karras, Tero, et al. "Progressive growing of gans for improved quality, stability, and variation." arXiv preprint arXiv:1710.10196 (2017).
- **Miyato, Takeru, et al. "Spectral Normalization for Generative Adversarial Networks."**

# Project plan
Right now I have no better place to write this so I'll do it here. Due to the long time consumption of the experiments I propose focusing on two things with two corresponding large-scale experiments. Progressive growing and triple-GAN. Firstly i will design a new training framework with these constellations in mind, thereafter I will test how well the progressive-growing works. When this have been tested I will focus on smaller rapid experiments on low-resolution images for a while to manage randomness and variation as well as getting the triple-GAN constellation to work properly. When this have beem performed I will scale up for a large experiment resulting in a high-resolution GAN.
