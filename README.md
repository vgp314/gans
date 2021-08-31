## Couser 1 - Build Basic Generative Adversarial Networks (GANs)


### Week1
	- Generative Models
	- Real Life GANS
	- Pre trained model exploration
	- Intuition Behing Gans
	- Discriminator
	- Generator
	- BCE cost function
	- Assigment:
		1) Build a first GAN that can generate hand-written images of digits (0-9).
		2) Build the generator and discriminator components of a GAN from scratch.
		3) Create generator and discriminator loss functions.
		4) Train your GAN and visualize the generated images.

### Week2
	- Activations
	- Batch Normalization (Explained)
	- Internal covariate shift
	- Convolutions
	- Pooling and Upsampling
	- Transposed Convolutions
	- Deep Convolutional GAN (DCGAN)
	- Assigment:
		1) Implement a Deep Convolutional GAN (DCGAN), a very successful and influential GAN model developed in 2015.
		2) Build a GAN that can generate hand-written images of digits (0-9).
		

	
### Week3
	- Mode Collapse
	- Problem with BCE Lost
	- Earth Movers Distance
	- Wassertein Lost
	- 1-Lipshitz Continous Enforcement (Gradient Penalty)
	- WGAN
	- Assigment:
		1) Build a Wasserstein GAN with Gradient Penalty (WGAN-GP) that solves some of the stability issues with the GANs that you have been using up until this point
	
### Week4
	- Condicional Generation
	- Assigment 1:
		1) Make a conditional GAN in order to generate hand-written images of digits, conditioned on the digit to be generated (the class vector). 
	- Controlable Generation
	- Challenges in controlable generation
	- Classifier Gradients
	- Disentanglement
	- Assingment 2:
		1) Implement a GAN controllability method using gradients from a classifier. 
		2) By training a classifier to recognize a relevant feature, you can use it to change the generator's inputs (z-vectors) to make it generate images with more or less of that feature.
		


## Couser 2 - Build Better Generative Adversarial Networks (GANs) 

### Week 1 
	- How to Evaluate GANS?
	- Comparing Images
	- Inception V3 and Embeddings
	- Sampling and Truncation
	- Precision and Recall	
	- Fréchet Inception Distance
	- Assignment:
		1) Understand the challenges associated with evaluating GANs.
    		2) Write code to evaluate the Fréchet Inception Distance.
    		
### Week 2
	- Disavantages of GANS
	- Alternatives of GANS
	- Machine Bias
	- Fairness
	- Ways that bias is introduced
	- Assignment:
		1) Be able to use a classifier to try and detect biases in a GAN by analyzing the generator's implicit associations.
### Week 3
	- Gans Improvements
	- Style GAN Overview
	- Progressive Growing
	- Noise Mapping Network
	- Adaptive Instance Normalization (AdaIN)
	- Style and Stochastic Variation
	- Assigment:
		1)  Implement various components of StyleGAN, including the 
			a) truncation trick
			b) the mapping layer
			c) noise injection
			d) adaptive instance normalization (AdaIN)
			e) progressive growing.

