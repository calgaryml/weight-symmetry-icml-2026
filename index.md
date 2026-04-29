---
layout: default
---

<!--| **Workshop Title** | {{ site.title }} |-->

| **Date** | One-day workshop on Friday, July 10, 2026 |
| **Location** | Coex Convention & Exhibition Center, Seoul, South Korea |
| **Submission** | Deadline ~~April 30, 2026 (AOE)~~ → **May 8, 2026 (AOE)** on [OpenReview](https://openreview.net/group?id=ICML.cc/2026/Workshop/WSS) |
| **Latest News** | Follow us at [@weightsymmetry](https://twitter.com/weightsymmetry) on X/Twitter for the updates! |

# Overview

Neural network weight spaces have a rich geometric structure, shaped by symmetries inherent to the architecture. Even the simplest MLP exhibits neuron permutation symmetries, meaning that swapping any two neurons in a layer along with their weights does not change the network function. Modern architectures introduce many more: attention mechanisms add continuous rotation symmetries, nonlinearities and normalization layers create scaling symmetries, and multi-head and mixture of experts architectures introduce permutation symmetries over heads and experts. Altogether, these symmetries shape the loss landscape and training dynamics as well as play an important role in model analysis, merging, and learning from model weights.

This workshop aims to deepen the fundamental understanding of weight-space symmetries and their effects, and to translate these insights into practical and scalable methods with diverse applications.

**Topics of interest include:**
- Characterizing weight-space symmetries across model architectures.
- Loss landscape structure, training dynamics, and symmetry-aware optimization.
- Linear mode connectivity and model merging.
- Analysis of model weights and weight-space learning.
- Other applications: compression, quantization, uncertainty quantification, model safety, etc.

**Questions?**
Contact us at [weightsymmetry@googlegroups.com](mailto:weightsymmetry@googlegroups.com) or [@weightsymmetry](https://twitter.com/weightsymmetry).

<!--# Background
Neural networks are highly over-parameterized models whose weight spaces exhibit rich symmetries. Key examples include **permutation symmetries** in MLPs and convolutional layers [(Ainsworth et al., 2023\)](https://openreview.net/forum?id%3Dis_pjY5786W), **rotation and attention-head symmetries** in transformers [(Tran et al., 2025\)](https://openreview.net/forum?id=ogO6DGE6FZ); [(Knyazev et al., 2025\)](https://openreview.net/forum?id=ogO6DGE6FZ); [(Theus et al., 2025\)](https://openreview.net/forum?id=ogO6DGE6FZ), and **scale invariances** from nonlinearities and normalization layers [(Chen et al., 1993\)](https://doi.org/10.1162/neco.1993.5.6.910); [(Phuong & Lampert, 2020\)](https://openreview.net/forum?id%3DB1gYUnNtvH); [(Godfrey et al., 2022\)](https://proceedings.neurips.cc/paper_files/paper/2022/hash/4db67f56d787729227653d9378129e92-Abstract-Conference.html); [(Kalogeropoulos et al., 2024\)](https://proceedings.neurips.cc/paper/2024).  
These symmetries create large equivalence classes of functionally identical solutions and have profound implications for the structure of the loss landscape, optimization, and design of practical algorithms. While significant progress has been made in characterizing these symmetries and their effects, a unified understanding remains elusive [(Zhao et al., 2026\)](https://openreview.net/forum?id=jLpWq5QY6I).  
Simultaneously, there is growing interest in practical applications, such as:

* **Training acceleration** [(Yi, 2022\)](https://proceedings.mlr.press/v180/yi22a.html); [(Chijiwa, 2024\)](https://openreview.net/forum?id=bWNJFD1l8M)  
* **Model merging** [(Stoica et al., 2024\)](https://openreview.net/forum?id%3DN79vY9B6Zk); [(Verma & Elbayad, 2024\)](https://openreview.net/forum?id=jLpWq5QY6I); [(Theus et al., 2025\)](https://openreview.net/forum?id=ogO6DGE6FZ)  
* **And more...**

The goal of this workshop is to bring together researchers from academia and industry to translate theoretical advances in weight-space symmetries into practical, scalable methods, fostering a coherent framework and highlighting approaches that are computationally feasible at scale.
-->
