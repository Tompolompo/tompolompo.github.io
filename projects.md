---
layout: page
title: Projects
permalink: /projects/
---
## University Projects
Below are some selected data science projects I've done in my master. Have a look at my [cv](/cv/) to see what other courses I've taken.
### Deep learning - *fall 2021*
In this course we learned about various deep learning techniques and implemented some of them using **pytorch** . For the heavy computations we relied on **cloud computing** via Google Cloud. Some of the projects were:
- Image classifiers:
	- with simple **convolutional nets**
	- using **transfer learning** with the VGG16 architecture
- **Recurrent Neural Networks**: 
	- predict nationalities of names
- **Transformers**: 
	- sentiment analysis
- **Reinforcement Learning**: 
	- model free RL on grid worlds
	- Deep Q-learning on the CartPole environment
- **CycleGAN**: ([report](./files/Deep_Learning_Project___Report.pdf))
	- **U-Net** and **PatchGAN** architectures 
	- style and morphological transfer betwee images of two domains

### Advanced simulation and machine learning - *fall 2021*
In this course we used many ML-methods rooted in Bayesian statistics. Some of the projects we did in python were
- Bayesian inference on generalized linear models ([report](./files/TIF345___Project_1.pdf))
	- Using Markov chain Monte Carlo (MCMC) sampling we fitted different cosmological models, including error modelling, on Type 1a supernovea data
- Comparison of advanced linear regression models ([report](./files/TIF345___Project_2a.pdf))
	- Estimated effective cluster interaction coefficients inferred by OLS, Ridge, covariance method, full Bayesian analysis (MCMC) and automatic relevance detection regression (ARDR)
- Global optimization ([report](./files/TIF345___Project_2b.pdf))
	- With Gaussian processes we efficiently found global minima of a multimodal surface using a LCB Aquisition function

### Advanced probabilistic machine learning - *fall 2021*
This was mainly a theoretical course where we covered many techniques from Bayesian statistics including Bayesan inference, classification, Bayesian graphical models, Belief propagation, Monte Carlo inference, variational inference and unsupervised learning. We explored some of these methods in python projects:
- Bayesian inference and classification
- Image denoising with Markov random fields
- Gibbs and importance sampling

### Learning from data - *fall 2020*
The course introduced a variety of central algorithms and methods essential for performing scientific data analysis using Bayesian inference and machine learning. Two selected projects were
- Parameter estimation ([report](./files/Project_1_Learning_from_data.pdf))
	- MCMC sampling to estimate parameters of an effective field theory
	- Extensive Bayesian comparison between different models and priors
- Solving the chaotic three-body problem with deep neural networks ([report](./files/Project_2_Learning_from_data.pdf))
	- using tensorflow we accurately predicted the trajectories of three bodies influenced by gravity. Many order of magnitude faster than the state of the art algorithm. 
	- constructed a custom loss function to improve energy conservation


<!---### Computational physics - *fall 2020*--->

<!---### Algorithms in finance - *spring 2020*--->

---
## Hobby Projects
### Reinforcement Learning - *summer 2021*
I created a few simple games using **pygame** that I then trained an RL-agent using **Deep-Q learning** to play. In one of the games, the agent gained super-human skills playing the game (a lot better than me).

### Interpretability of neural networks - *summer 2021*
As part of my *AGI safety fundamentals* fellowship (see  [cv](/cv/)), I explored interpretability of neural networks. I trained simple image classifiers on the MNIST dataset using **tensorflow** and inspected individual neurons by maximizing their activation with respect to the input image. 

### Quantitative finance - *summer 2019*
In the summer of 2019, between trainings and competitions, I decided that I wanted to learn **python**. To this end, I wanted to create a project so I could learn python in a fun way. At that time, I was interested in quantitative finance so I spent the summer break developing a backtesting program for the evaluation of trading algorithms on data scraped from Yahoo Finance. I also built a webpage that tracked the progress of an algorithm that ran live with mock capital.


---

Email me at [tomas.lundberg95@gmail.com](mailto:tomas.lundberg95@gmail.com).