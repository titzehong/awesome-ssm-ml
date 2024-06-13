# Awesome State-Space Resources for ML

**Contributions are welcome! Please read the [contribution guidelines](#contributions) before contributing.**

## Table of Contents

- [Tutorials](#tutorials)
- [Surveys](#surveys)
- [Books](#books)
- [Foundation](#foundation)
- [Architecture](#architecture)
- [Language](#language)
- [Parameterization and Initialization](#ssm-parameterization-and-initialization)
- [Miscellaneous](#miscellaneous)

## Tutorials <a name="tutorials"></a>

#### Blogposts
1. [S4 Series](https://hazyresearch.stanford.edu/blog/2022-01-14-s4-1)
2. [The Annotated S4](https://srush.github.io/annotated-s4/)
3. [The Annotated S4D](https://srush.github.io/annotated-s4/s4d.html)
4. [The Annotated Mamba](https://srush.github.io/annotated-mamba/hard.html) [[code]](https://github.com/srush/annotated-mamba)
5. [Mamba: The Easy Way](https://jackcook.com/2024/02/23/mamba.html)
6. [Mamba: The Hard Way](https://srush.github.io/annotated-mamba/hard.html)
7. [A Visual Guide to Mamba and State Space Models](https://open.substack.com/pub/maartengrootendorst/p/a-visual-guide-to-mamba-and-state)
8. [State Space Models: A Modern Approach](https://probml.github.io/ssm-book/root.html)
9. [State Space Duality (Mamba-2)](https://tridao.me/blog/2024/mamba2-part1-model/)


## Surveys (Structured State Space Models) <a name="surveys"></a>
1. [Modeling Sequences with Structured State Spaces](https://www.proquest.com/docview/2880853867?pq-origsite=gscholar&fromopenview=true&sourcetype=Dissertations%20&%20Theses)
2. [State Space Model for New-Generation Network Alternative to Transformers](https://arxiv.org/abs/2404.09516)
3. [Mamba-360: Survey of State Space Models as Transformer Alternative for Long Sequence Modelling: Methods, Applications, and Challenges](https://arxiv.org/abs/2404.16112)
4. [A Survey on Visual Mamba](https://arxiv.org/abs/2404.15956)

## Books (Classical State Space Models) <a name="books"></a>
1. [Linear State-Space Control Systems](https://onlinelibrary.wiley.com/doi/book/10.1002/9780470117873)
2. [Principles of System Identification Theory and Practice](https://www.taylorfrancis.com/books/mono/10.1201/9781315222509/principles-system-identification-arun-tangirala)

## Foundation
1. [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752) [[code]](https://github.com/state-spaces/mamba)
2. [Structured state-space models are deep Wiener models](https://arxiv.org/abs/2312.06211)
3. [State-space Models with Layer-wise Nonlinearity are Universal Approximators with Exponential Decaying Memory](https://arxiv.org/abs/2309.13414)
4. [Repeat After Me: Transformers are Better than State Space Models at Copying](https://arxiv.org/abs/2402.01032)
5. [Theoretical Foundations of Deep Selective State-Space Models](https://arxiv.org/abs/2402.19047)
6. [The Hidden Attention of Mamba Models](https://arxiv.org/abs/2403.01590)
7. [The Expressive Capacity of State Space Models: A Formal Language Perspective](https://arxiv.org/abs/2405.17394)
8. [Simplifying and Understanding State Space Models with Diagonal Linear RNNs](https://arxiv.org/abs/2212.00768)
9. [Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality](https://arxiv.org/abs/2405.21060)

## Architecture
1. [S5: Simplified State Space Layers for Sequence Modeling](https://arxiv.org/abs/2208.04933) (ICLR 2023) [[code]](https://github.com/lindermanlab/S5)
2. [Long range language modeling via gated state spaces](https://arxiv.org/abs/2206.13947) (ICLR 2023)
3. [Pretraining Without Attention](https://arxiv.org/abs/2212.10544) [[code]](https://github.com/jxiw/BiGS)
4. [MoE-Mamba: Efficient Selective State Space Models with Mixture of Experts](https://arxiv.org/abs/2401.04081) [[code]](https://github.com/llm-random/llm-random)
5. [LOCOST: State-Space Models for Long Document Abstractive Summarization](https://arxiv.org/abs/2401.17919) [[code]](https://github.com/flbbb/locost-summarization)
6. [BlackMamba: Mixture of Experts for State-Space Models](https://arxiv.org/abs/2402.01771) [[code]](https://github.com/Zyphra/BlackMamba)
7. [DenseMamba: State Space Models with Dense Hidden Connection for Efficient Large Language Models](https://arxiv.org/abs/2403.00818) [[code]](https://github.com/WailordHe/DenseSSM)
8. [ZigMa: Zigzag Mamba Diffusion Model](https://arxiv.org/abs/2403.13802) [[code]](https://github.com/CompVis/zigma) [[website]](https://taohu.me/zigma/)
9. [Jamba: A Hybrid Transformer-Mamba Language Model](https://arxiv.org/abs/2403.19887)
10. [Block-State Transformers](https://arxiv.org/abs/2306.09539)
11. [Efficient Long Sequence Modeling via State Space Augmented Transformer](https://arxiv.org/abs/2212.08136)
   
## Language
1. [Hungry Hungry Hippos: Towards Language Modeling with State Space Models](https://arxiv.org/abs/2212.14052) (ICLR 2023) [[code]](https://github.com/HazyResearch/H3)
2. [Long range language modeling via gated state spaces](https://arxiv.org/abs/2206.13947) (ICLR 2023) [[code]](https://github.com/lucidrains/gated-state-spaces-pytorch.git)
3. [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752) [[code]](https://github.com/state-spaces/mamba)
4. [MambaByte: Token-free Selective State Space Model](https://arxiv.org/abs/2401.13660) [[code]](https://github.com/lucidrains/MEGABYTE-pytorch)
5. [Can Mamba Learn How to Learn? A Comparative Study on In-Context Learning Tasks](https://arxiv.org/abs/2402.04248)

## SSM Parameterization and Initialization
1. [Combining Recurrent, Convolutional, and Continuous-time Models with Linear State-Space Layers](https://arxiv.org/abs/2110.13985) (NeurIPS 2021)
2. [Eﬃciently Modeling Long Sequences with Structured State Spaces](https://arxiv.org/abs/2110.13985) (ICLR 2022)
3. [On the Parameterization and Initialization of Diagonal State Space Models](https://arxiv.org/abs/2206.11893) (NeurIPS 2022)
4. [Diagonal State Spaces are as Effective as Structured State Spaces](https://arxiv.org/abs/2203.14343) (NeurIPS 2022) [[code]](https://github.com/ag1988/dss)
5. [How to Train your HIPPO: State Space Models with Generalized Orthogonal Basis Projections](https://arxiv.org/abs/2206.12037) (ICLR 2023)
7. [Robustifying State-space Models for Long Sequences via Approximate Diagonalization](https://arxiv.org/abs/2310.01698)
8. [StableSSM: Alleviating the Curse of Memory in State-space Models through Stable Reparameterization](https://arxiv.org/abs/2311.14495)
9. [Spectral State Space Models](https://arxiv.org/abs/2312.06837)

## Representation Power
1. [Understanding the differences in Foundation Models: Attention, State Space Models, and Recurrent Neural Networks](https://arxiv.org/abs/2405.15731)
2. [The Expressive Capacity of State Space Models: A Formal Language Perspective](https://arxiv.org/abs/2405.17394)
3. [Repeat After Me: Transformers are Better than State Space Models at Copying](https://arxiv.org/abs/2402.01032)

## SSD / Linear Attention Variants
1. [Gated Linear Attention Transformers with Hardware-Efficient Training](https://arxiv.org/abs/2312.06635)
2. [Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention](https://arxiv.org/abs/2006.16236)
3. [GateLoop: Fully Data-Controlled Linear Recurrence for Sequence Modeling](https://arxiv.org/abs/2311.01927)
4. [Retentive Network: A Successor to Transformer for Large Language Models](https://arxiv.org/pdf/2307.08621)

## Other Recurrent Models / Non - Attention
1. [RWKV: Reinventing RNNs for the Transformer Era](https://arxiv.org/abs/2305.13048)
2. [Eagle and Finch: RWKV with Matrix-Valued States and Dynamic Recurrence](https://arxiv.org/abs/2404.05892)
3. [xLSTM: Extended Long Short-Term Memory](https://arxiv.org/abs/2405.04517)

## Miscellaneous
1. [Variational learning for switching state-space models](https://www.cs.toronto.edu/~hinton/absps/switch.pdf) (Neural Computation 2000)
2. [Liquid structural state-space models](https://arxiv.org/abs/2209.12951) (ICLR 2023)
3. [Resurrecting Recurrent Neural Networks for Long Sequences](https://arxiv.org/abs/2303.06349) (ICML 2023)
4. [Learning Low Dimensional State Spaces with Overparameterized Recurrent Neural Nets](https://arxiv.org/abs/2210.14064) (ICLR 2023)
5. [Never Train from Scratch: Fair Comparison Of Long- Sequence Models Requires Data-Driven Pirors](https://arxiv.org/abs/2310.02980)



## Contributions

🎉 Thank you for considering contributing to our Awesome State Space Models for Machine Learning repository! 🚀

### Contribute in 3 Steps:

1. **Fork the Repo:**
   Fork this repo to your GitHub account.

2. **Edit Content:**
   Contribute by adding new resources or improving existing content in the `README.md` file.

3. **Create a Pull Request:**
   Open a pull request (PR) from your branch to the main repository.

### Guidelines

- Follow the existing structure and formatting.
- Ensure added resources are relevant to State Space Models in Machine Learning.
- Verify that links work correctly.

### Reporting Issues

If you encounter issues or have suggestions, open an issue on the GitHub repository.

Your contributions make this repository awesome! Thank you! 🙌

## License

This project is licensed under the [MIT License](LICENSE).
