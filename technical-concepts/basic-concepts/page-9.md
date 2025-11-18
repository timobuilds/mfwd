# Page 9

### Diffusers

Diffusion models are a relatively recent addition to a group of algorithms known as 'generative models. The goal of generative modeling is to learn to **generate** data, such as images or audio, given a number of training examples. A good generative model will create a **diverse** set of outputs that resemble the training data without being exact copies.

The secret to diffusion models' success is the iterative nature of the diffusion process. Generation begins with random noise, but this is gradually refined over a number of steps until an output image emerges. At each step, the model estimates how we could go from the current input to a completely denoised version. However, since we only make a small change at every step, any errors in this estimate at the early stages (where predicting the final output is extremely difficult) can be corrected in later updates.
