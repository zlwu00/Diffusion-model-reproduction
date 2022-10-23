# Diffusion-model-reproduction

## Denoising Diffusion Probabilistic Models(DDPM) reproducing shape 's'
The original sampled datasets look like a shape 's' as follows:


![image](https://user-images.githubusercontent.com/90286636/196898622-fc101a2a-5e3f-4929-92ac-7fa476f13468.png)

The diffusion model first add small amount of Gaussian noise to the sample in T steps, producing a sequence of noisy samples.

![image](https://user-images.githubusercontent.com/90286636/196899447-33e8af92-91c0-4ca0-8153-7bd331e97409.png)

Then reverse the above process and recreate the true sample from a Gaussian noise input.

![image](https://user-images.githubusercontent.com/90286636/196899820-47d97010-1ae7-4aa0-8162-6f567fddd6f6.png)

The details of DDPM can be seen in probabilitistic_diffusion_model.ipynb

## Score_Diffusion_Model

Reference :

Song Y, Sohl-Dickstein J, Kingma D P, et al. Score-based generative modeling through stochastic differential equations[J]. arXiv preprint arXiv:2011.13456, 2020.

https://yang-song.net/blog/2021/score/

https://www.bilibili.com/video/BV1Dd4y1A7oz/?spm_id_from=333.788&vd_source=610c267a4ef9add9ee52ada52ef9c380

Reproduce MNIST pictures with score-based diffusion model

![image](https://user-images.githubusercontent.com/90286636/197397846-1d987095-eec2-4fee-9b96-c6d1c681ad45.png)

The details of score-based diffusion model can be seen in Score_Diffusion_Model.ipynb
