# Generative AI + Biology Basics

A guide to ramping up for projects at the intersection of generative AI and biology.

## Optimization/Deep Learning

<details>
<summary>What is the difference between stochastic gradient descent and Adam?</summary>
<br>
Optimization Algorithms, SGD, Adam
Memory and performance
Code example link in JAX/PyTorch
</details>

- Train/validation/test splits and cross-validation
- Overhead for multi-GPU training (analyze with NVIDIA nsight)
- Implement a diffusion model
- Implement a normalizing flow
- How do you train a normalizing flow?
- Implement flow matching
- Distillation, cross-distillation
- Fully sharded data parallelism
- torch.einsum
- DeepLift

<details>
<summary>VJP</summary>
<br>
XXX
</details>

<details>
<summary>JVP</summary>
<br>
XXX
</details>

## Coding

- counters
- abstract classes
- version control
- Big O analysis for performance/memory
- () matching leetcode easy problem
- Kabsch algorithm
- pandas and SQL
- Dijkstra's algorithm
- topological data analysis
- merge tree
- contour tree

## Math/Numerical Methods

- log normal distribution
- What is a random variable? 
- How do you sample a PDF/posterior distribution? (https://twiecki.io/blog/2015/11/10/mcmc-sampling/)
(https://pj.freefaculty.org/guides/stat/Distributions/DrawingRandomSamples/DrawingSamples.pdf)

## Large Language Models

- ELMO
- BERT
- GPT
- T5
- Transformer
- How to process really long sequences with attention layer
- Code an attention layer

## Structural Biology/Drug Design

- DiffDock (great at pocket identification, weakness is the pose in the pocket)
- EquiDock
- AlphaFold
- How does AlphaFold-multimer differ from AlphaFold-monomer?
- Force fields/molecular dynamics
- Flow-Matching: Efficient Coarse-Graining of Molecular Dynamics without Forces: https://pubs.acs.org/doi/full/10.1021/acs.jctc.3c00016
- RNA structure
- Designing proteins
- When to use equivariance
- Why is there no equivariance in AlphaFold 3? Effectively data augmentation is used
- FAPE loss
- Kabsch vs FAPE, pros/cons
- RFDiffusion
- Explain RosettaFold and difference to AlphaFold: geometric operations, 1D, 2D, 3D tracks/templates, SE(3) equivariant transformer
- Protein MPNN to generate a sequence from a protein
- RoseTTAfold all atom
- PoseBusters
- PDBBind
- Autodock Vina
- DockGen
- cryoDRGN
- Recursion’s Phenom-Beta
- LDDT
- DockQ
- Geneformer
- Molprobity
- Rotamers
- [Solving Inverse Problems in Protein Space Using Diffusion-Based Priors](https://arxiv.org/pdf/2406.04239)
- [Designing DNA With Tunable Regulatory Activity Using Discrete Diffusion](https://www.biorxiv.org/content/10.1101/2024.05.23.595630v1)
- [Out of Many, One: Designing and Scaffolding Proteins at the Scale of the Structural Universe with Genie 2](https://arxiv.org/abs/2405.15489)
- [Deep learning and alignment of spatially resolved single-cell transcriptomes with Tangram](https://www.nature.com/articles/s41592-021-01264-7)
- [Geneformer paper: Transfer learning enables predictions in network biology](https://www.nature.com/articles/s41586-023-06139-9)
- [A dataset of alternately located segments in protein crystal structures](https://www.nature.com/articles/s41597-024-03595-4)
- EigenFold

- [AlphaFold Meets Flow Matching for Generating Protein Ensembles](https://www.youtube.com/watch?v=yDDXF6XJZck&t=29s&ab_channel=ValenceLabs)
- CellOracle
- SCENIC+
- scRNA-seq
- scATAC-seq

<details>
<summary>Someone comes to you with a model that works well for binding affinities of small molecules to a given protein. What checks do you run before running experiments to see how the model generalizes?</summary>
<br>
XXX
</details>

## LLMs + Biology

- ESMFold
- Soloseq
- CodonBERT: Large Language Models for mRNA design and optimization