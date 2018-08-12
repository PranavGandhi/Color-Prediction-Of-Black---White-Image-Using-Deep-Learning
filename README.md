# Color-Prediction-Of-Black---White-Image-Using-Deep-Learning
Given a grayscale photograph as input, this paper attacks the problem of hallucinating
a plausible color version of the photograph. This problem is clearly under constrained, so
previous approaches have either relied on significant user interaction or resulted in desaturated
colorizations. We propose a fully automatic approach that produces vibrant and realistic
colorizations. We embrace the underlying uncertainty of the problem by posing it as a
classification task and use class-rebalancing at training time to increase the diversity of colors in
the result. The system is implemented as a feed-forward pass in a CNN at test time and is trained
on over a million color images. I present a convolutional-neural-network-based system that
faithfully colorizes black and white photographic images without direct human assistance. We
explore various network architectures, objectives, color spaces, and problem formulations. The
final classification-based model we build generates colorized images that are significantly more
aesthetically-pleasing than those created by the baseline regression-based model, demonstrating
the viability of our methodology and revealing promising avenues for future work.
