# Loss Landscapes of Regularized Linear Autoencoders
##### [Daniel Kunin](http://daniel-kunin.com/), [Jonathan M. Bloom](https://www.broadinstitute.org/bios/jonathan-bloom), [Aleksandrina Goeva](https://macoskolab.com/about-us/), [Cotton Seed](https://www.broadinstitute.org/bios/cotton-seed)

Autoencoders are a deep learning model for representation learning. When trained to minimize the Euclidean distance between the data and its reconstruction, linear autoencoders (LAEs) learn the subspace spanned by the top principal directions but cannot learn the principal directions themselves. In this paper, we prove that L2-regularized LAEs learn the principal directions as the left singular vectors of the decoder, providing an extremely simple and scalable algorithm for rank-k SVD. More generally, we consider LAEs with (i) no regularization, (ii) regularization of the composition of the encoder and decoder, and (iii) regularization of the encoder and decoder separately. We relate the minimum of (iii) to the MAP estimate of probabilistic PCA and show that for all critical points the encoder and decoder are transposes. Building on topological intuition, we smoothly parameterize the critical manifolds for all three losses via a novel unified framework and illustrate these results empirically. Overall, this work clarifies the relationship between autoencoders and Bayesian models and between regularization and orthogonality. 

[Paper](https://arxiv.org/pdf/1901.08168.pdf), [Code](https://github.com/danielkunin/Regularized-Linear-Autoencoders/blob/master/Loss%20Landscapes%20of%20Regularized%20Linear%20Autoencoders%20Code.ipynb), [Erratum](https://github.com/danielkunin/Regularized-Linear-Autoencoders/blob/master/erratum.md).

Feedback welcome! Contact Daniel and Jon: kunin@stanford.edu, jbloom@broadinstitute.org
