---
title: Higher-Order Factorization for Latent Dynamic Embeddings
summary: Most natural phenomena are governed by dynamic processes, resulting in observed time-varying data. I am developing methods that can better capture the dynamic processes embedded in observed data. Focusing on brain network data, I am identifying latent embedding models for learning dynamics of networks, including tensor factorization, sparse regression, and autoencoder models. This enhances methods at the edge of machine learning and dynamical systems theory.

tags:
- Coupled Oscillators
- Dynamical Systems
- Temporal Embeddings
- Dynamic Embeddings
- Latent Variable Modeling
- Tensor Factorization
- Tensor Decomposition

date: "2022-03-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point:

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://https://sociophysio.org/current-projects/
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---
Most natural phenomena are governed by dynamic processes, resulting in observed time-varying data. However, such data are often represented as static in nature for analysis. This is especially true for graph/network based data. Thus, it is important to develop methods that can better capture the dynamic processes embedded in observed data. One way to do this is to develop latent dynamic embeddings which encode such information. 

To explore this, I have focused on an area where such analytical development is particularly salient: brain networks. The study of brain networks has driven much progress in understanding the principles and mechanisms underlying complex cognitive processes. Brain networks as a representation come with immense complexity. The brain itself is incredibly complex, with multiscale and multi-regional dynamics governing its function. Further complexity is introduced when considering the variability of individual brains from person to person, and the array of factors that can influence or affect brain function, and as a result, brain activity and behavior.

In order to begin to develop an understanding of these dynamics, I have adopted the use of the Kuramoto-Sakaguchi coupled oscillator model to generate controllable, but biologically plausible synthetic data. This extends the recent research by (Sporns Lab) on how modular organization of structural connectivity influences high-amplitude co-fluctuations in functional connectivity dynamics, which leverages the same oscillator model to interrogate the effect of topology on functional connectivity. By utilizing this biologically plausible phenomenological model to synthesize data, we may identify better analytical methods to estimate complex network dynamics.


Most studies are still limited to analysis based on statistical heuristics. This limits our understanding of the potential multiscale dynamics which govern dynamical behavior of brain networks. A potential approach for overcoming this is the application of higher order factorization methods, also dubbed tensor factorization. A natural extension of commonly utilized matrix factorization methods, tensor factorizations are utilized to derive low-rank latent representations of data which correspond to potential factors that underlie observed behavior in data. The application of tensor factorization to synthetic oscillator model data, in an effort to capture the latent dynamics of time-varying brain networks, may allow us to more effectively analyze dynamics in real-world data beyond statistical heuristics.

There are still several challenges to this end. Conceiving the appropriate factorization method for decomposing data is not a trivial problem. Being able to identify factors which correspond to underlying dynamics may not be straightforward either. However, innovations at the edge of machine learning and dynamical systems theory may provide context for choosing an effective factorization method. In our study, we will be interrogating a number of methods that can address these constraints, including sparse regression and autoencoder models
