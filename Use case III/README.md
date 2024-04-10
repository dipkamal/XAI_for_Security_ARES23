
# Use-case-III: Adversarial Image Detection 

Feature attribution for an adversarial sample differs from its benign counterpart because the adversarial perturbation flips the model prediction, causing the explanation method to attribute importance to different features. In the paper, we provide a motivating example, displaying the heatmap for the benign and corresponding adversarial counterpart of the CIFAR-10 dataset using the gradient method (also known as saliency) and integrated gradient. Interestingly, this difference in feature attribution can be measured using simple statistics of dispersion like median absolute deviation (MAD).

In this use case, we demonstrate the application of explanation methods in the detection of adversarial samples using a threshold strategy on the statistics of feature attribution. This folder consists of the following files: 
- Plots: This folder contains some plots from our experiments. 
- detect_adv_samples_mnist.pynb: This notebook contains adversarial detection for mnist samples. 
- detect_adv_samples_cifar.pynb: This notebook contains adversarial detection for cifar-10 samples.

