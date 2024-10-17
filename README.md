# Learning-Generative-Models
This repo contains all the assignments from the LGM course

Deep Learning techniques have gained popularity and yielded astonishing results in a wide range of applications, like computer vision or speech recognition. In most of these applications, deep neural nets are trained in a supervised way, i.e., the network is trained to predict a particular label for high-dimensional data. In order to perform well, they need large amounts of data.

In many real-world applications, the amount of data is either limited or it is not annotated with the desired labels. For instance, training a deep neural network to reliably detect a malfunction in a nuclear power plant would require a lot of measurements during melt-down, which obviously is infeasible.

Generative models can be used to tackle such problems. They learn to represent the probability distribution over multiple variables from training data. While ordinary deep neural networks may discard any information unrelated to the desired prediction, generative models learn to represent the data in its entirety. As such, they can be applied to tasks like imputing missing values, repairing damaged data, detecting anomalies or generating new data from the learnt distribution.

The course will first focus on understanding and applying shallow and deep energy-based models as a particular type of generative models. Furthermore, the course will cover more recent generative models, like Variational Autoencoders (VAEs), Generative Adversarial Networks (GANs), Autoregressive Models, Diffusion Models, and more. For implementation, I have used Python and TensorFlow.
