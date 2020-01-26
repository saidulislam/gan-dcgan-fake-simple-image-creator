# gan-dcgan-fake-simple-image-creator

This notebook is all about building a DCGAN (Deep Convolutional GAN) that can generate new images that look like house addresses from the Google Streetview dataset, SVHN.
<br/><br/>
Everything you need is in DCGAN_fake_simple_image_creator.ipynb
<br/><br/><br/>
<b>High-level Instructions</b>
<br/>
Load in SVHN data<br/>
Pre-process that data, scaling the pixel values to a desired range<br/>
Define two adversarial networks; a Discriminator and Generator that utilize convolutional or transpose convolutional layers<br/>
Train the networks and generate new images<br/>
<br/>
<br/>
<b>The recommendation is this:</b>
<br>
<li>Load in data, test functions and models (checking parameters and doing a short training loop) while in CPU (non-enabled) mode
<li>When you're ready to extensively train and test your model, enable GPU to quickly train the model!
<br/>
All models and data they see as input will have to be moved to the GPU device, so take note of the relevant movement code in the model creation and training process.
