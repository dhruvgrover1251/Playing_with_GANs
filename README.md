# Playing_with_GANs
<p>This repository consist of implementation of DCGANs on 2 datasets (celeba and MNIST) for generating completely new looking images of faces and numbers respectively.</p>
<p> TO understand GANs here is the small summary of first paper(https://arxiv.org/pdf/1406.2661.pdf)</p>
<h3> Generative Adversarial Nets(Summary) </h3>
<h4> Introduction</h4>
<p> GANs take a game-theoretical approach: learn to generate from 2 player games to come over the problem of the intractable density function.
This model doesn’t assume explicit density function as in the case of VAEs.</p>
<h4> Adversarial networks </h4>
<p> In this, we have two types of networks,</p>
1. Generator network:<br>
<p>Try to fool discriminator by generating real looking images.</p>
<p>To learn the generator’s distribution p<sub>g</sub> over data x, we define a prior on input noise variables p<sub>g</sub>(z), then represent a mapping to data space as G(z; theta<sub>g</sub>), where G is a differentiable function represented by a multilayer perceptron with parameters g.</p>
2. Discriminator network: <br>
<p>Try to distinguish between real and fake images.</p>
<p>It is a second multilayer perceptron D(x;theta<sub> d</sub>) that outputs a single scalar. D(x) represents the probability that x came from the data rather than p<sub>g.</sub></p>


 
