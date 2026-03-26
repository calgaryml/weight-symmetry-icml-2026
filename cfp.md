---
layout: default
---

# Call for Papers
<!-- 
The submission deadline is **April 24, 2026 (23:59 AoE)**. -->

<!-- | **Submission**          |[https://openreview.net/group?id=ICML.cc/2026/Workshop/TDA_and_Beyond](https://openreview.net/group?id=ICML.cc/2026/Workshop/WeightSymmetry)| -->

| **Submission Portal**          |TBA|
| **Deadline**            |April 24, 2026 (23:59 AoE)|
| **Author notification** |May 15, 2026, AOE (23:59 AoE)|

We welcome all original research papers of up to 4 pages in length,
using the template provided [below](#style). This length does not include
references or any supplementary materials. Reviewers are *not* obliged
to read supplementary materials when reviewing the paper.  Submissions
should be a single file in `.pdf` format. The review process is
*double-blind*, so please ensure that all papers are appropriately
anonymised. 

<!-- 
We also welcome extended abstracts of up to 2 pages in length that
describe open problems, novel applications, or challenges in
*Topological Data Analysis*, *Topological Machine Learning*, and related
areas&nbsp;(using the template provided [below](#style)). Again, this length does
not include references or any supplementary materials. -->

We also permit papers that have been recently published or are under
submission to another venue. Please mark such papers accordingly upon
submission. The page limit for these submissions is 4 pages.

Selected papers will be presented as brief 'spotlights' of 3 minutes length.
All authors of accepted papers will have the option to present their work in a live session.

This workshop is **non-archival**; even though all accepted papers will be
available on OpenReview, there are *no* formally-published proceedings.

# Style

We only accept submissions that have been prepared using LaTeX. Use the
following workshop style files for your submission (the PDF file is
provided as a preview of the expected style), in place of the standard ICML style file (`icml2026.sty`):

- [icml2026_weightsymmetry.sty](/assets/icml2026_weightsymmetry.sty)

# Scope and topics

Please find a list of topics of interested, sorted alphabetically. If
you are not sure whether your topic might be a good fit for the
workshop, feel free to contact us.

<!-- at [workshop@topology.rocks](mailto:workshop@topology.rocks). -->

## Topics of Interest
We welcome submissions on all topics related to weight-space symmetries, including but not limited to:

- **Understanding Loss Landscapes and Optimization**

   Weight-space symmetries fundamentally reshape the loss landscape by introducing functionally identical replicas of minima [Brea et al. (2019)](https://arxiv.org/abs/1907.02911); [Simsek et al. (2021)](https://proceedings.mlr.press/v139/simsek21a.html) that form continuous manifolds [Garipov et al. (2018)](https://proceedings.neurips.cc/paper/2018/hash/be3087e74e9100d4bc4c6268cdbe8456-Abstract.html); [Zhao et al. (2023)](https://openreview.net/forum?id=9ZpciCOunFb), along with symmetry-induced saddle points and low-curvature directions [Brea et al. (2019)](https://arxiv.org/abs/1907.02911). These structural properties complicate loss landscape analysis [Pittorino et al. (2022)](https://proceedings.mlr.press/v162/pittorino22a.html); [Lim et al. (2024)](https://openreview.net/forum?id=pCVxYw6FKg); [Michelucci (2022)](https://arxiv.org/abs/2211.06603); [Zhao et al. (2026)](https://openreview.net/forum?id=jLpWq5QY6I) and influence optimization dynamics [Laarhoven (2017)](https://arxiv.org/abs/1706.05350); [Tanaka & Kunin (2021)](https://openreview.net/forum?id=fiPtD7iXuhn); [Chen et al. (2023)](https://proceedings.neurips.cc/paper_files/paper/2023/hash/6e4432b912599d11609b9cdf98c823c5-Abstract-Conference.html); [Liu (2024)](https://proceedings.mlr.press/v41/ziyin24a.html).  

   Motivated by these effects, several recent works propose new optimization strategies, including symmetry-invariant methods [Neyshabur et al. (2015)](https://proceedings.neurips.cc/paper/2015/hash/2179899f8d5f782488f8286937e3bb67-Abstract.html); [Meng et al. (2019)](https://openreview.net/forum?id%3DS1glSj09KX); [Yi (2022)](https://proceedings.mlr.press/v180/yi22a.html) that constrain updates to symmetry-reduced manifolds, approaches exploiting symmetry to accelerate training via "teleportation" or transfer of trajectory segments [Armenta et al. (2023)](https://doi.org/10.3390/math11020480); [Zhao et al. (2022)](https://proceedings.neurips.cc/paper_files/paper/2022/hash/6b0445a6c4b2204c3e7f60037a4df15f-Abstract-Conference.html); [Zhao et al. (2024)](https://openreview.net/forum?id=L0r0GphlIL); [Chijiwa (2024)](https://openreview.net/forum?id=bWNJFD1l8M), and techniques that bias symmetry breaking to obtain solutions with desired properties [Silverstein et al. (2026)](https://arxiv.org/abs/2601.22257). In our workshop, we aim to connect theoretical research in this area and practical advances in model training.  

- **Linear Mode Connectivity (LMC) and Model Merging**

    Minima copies induced by weight symmetries motivated the LMC modulo permutation hypothesis: independently trained neural networks can be connected by a low-loss linear path once aligned via neuron permutations [Entezari et al. (2022)](https://openreview.net/forum?id%3DpUg_9_I9fE3); [Ainsworth et al. (2023)](https://openreview.net/forum?id%3Dis_pjY5786W). This hypothesis has become the cornerstone of approaches for merging models trained from different initializations [Ainsworth et al. (2023)](https://openreview.net/forum?id%3Dis_pjY5786W); [Stoica et al. (2024)](https://openreview.net/forum?id%3DN79vY9B6Zk); [Nasery et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ) and has also been extended to account for other weight-space symmetries [Horoi et al. (2024)](https://proceedings.mlr.press/v235/horoi24a.html); [Imfeld et al. (2024)](https://openreview.net/forum?id=FOSBQuXgAq); [Zhang et al. (2025)](https://openreview.net/forum?id=wBJIO15pBV).  
    
    Effective merging of independently trained models is key for combining knowledge across networks, reducing overall training costs, and enabling modular training. Despite the potential, it remains extremely challenging on large-scale models and tasks, such as transformers in large language models [Imfeld et al. (2024)](https://openreview.net/forum?id=FOSBQuXgAq); [Verma & Elbayad (2024)](https://openreview.net/forum?id=jLpWq5QY6I); [Hubara et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ); [Tran et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ); [Theus et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ). To address this open problem, we aim to promote discussion and research at the intersection of symmetry-aware model alignment methods and scalable merging solutions, including approaches for merging models trained from the same initialization [Mitchell et al. (2022)](https://openreview.net/forum?id%3Dis_pjY5786W); [Ilharco et al. (2023)](https://openreview.net/forum?id%3Dis_pjY5786W); [Yadav et al. (2023)](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e0c4369a19d26e4e08216f4995f59685-Abstract-Conference.html).  

- **Weight-Space Learning (WSL)**

    WSL is an emerging area focusing on learning the representation of neural network weights by taking into account their structure and symmetries [Eilertsen et al. (2020)](https://doi.org/10.3233/FAIA200208); [Knyazev et al. (2021)](https://proceedings.neurips.cc/paper/2021/hash/686950275816997092ed16f866465f21-Abstract.html); [Schürholt et al. (2022)](https://proceedings.neurips.cc/paper/2022/hash/1b73010b985472856f6c9d09c31405e3-Abstract.html); [Zhou et al. (2023)](https://proceedings.neurips.cc/paper_files/paper/2023/hash/4e078b665c370a2f153a83015f838615-Abstract-Conference.html); [Schürholt et al. (2024)](https://proceedings.mlr.press/v235/schurholt24a.html); [Kofinas et al. (2024)](https://openreview.net/forum?id=ogO6DGE6FZ); [Lim et al. (2024)](https://openreview.net/forum?id=pCVxYw6FKg).  

    This area has emerged from the synergy between the increasing number of trained checkpoints, the methods effectively learning such representations, and impactful applications, such as accelerating training [Knyazev et al. (2023)](https://proceedings.mlr.press/v202/knyazev23a.html); [Kofinas et al. (2024)](https://openreview.net/forum?id=ogO6DGE6FZ); [Knyazev et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ); [Zamir et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ); [Singh et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ); [Wang et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ); [Shou et al. (2025)](https://arxiv.org/abs/2505.20221), model merging [Navon et al. (2024)](https://proceedings.mlr.press/v235/navon24a.html) and editing [Mitchell et al. (2022)](https://openreview.net/forum?id%3Dis_pjY5786W). Our workshop will focus on identifying these key limitations of WSL, developing principled methods that are invariant or equivariant to weight-space symmetries, and understanding the geometry and topology of weight space.  

- **Other Applications**

    Accounting for weight-space symmetries can improve model compression [Li et al. (2024)](https://openreview.net/forum?id%3Dis_pjY5786W); [Chen et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ), quantization [Liu et al. (2025)](https://openreview.net/forum?id=ogO6DGE6FZ), uncertainty quantification [Laurent et al. (2024)](https://openreview.net/forum?id=FOSBQuXgAq); [Xiao et al. (2023)](https://arxiv.org/abs/2310.15045), and model safety [Peng et al. (2025)](https://proceedings.mlr.press/v267/peng25f.html). The workshop will highlight these broader applications and encourage discussion of symmetry-aware methods across diverse practical settings.  

