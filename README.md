# Deep Neural Network Based Attention Model for Structural Component Recognition

This is the tensorflow implementation of "Deep Neural Network Based Attention Model for Structural Component Recognition". This repository includes the proposed Synchronous Dual Attention Module, Batch of Multi-feature Attention Module and Parallel Excitation Module. The results folder contains the results and the visualizations using attention maps.

# Citation

If you are fully or partially using codes/results from this repository, please cite the following paper:

Sarangi, S. and Mandal, B. (2023). Deep Neural Network Based Attention Model for Structural Component Recognition. In Proceedings of the 18th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications - Volume 4: VISAPP, ISBN 978-989-758-634-7; ISSN 2184-4321, pages 317-326. DOI: 10.5220/0011688400003417.

The original paper can be accessed from here: 
https://www.scitepress.org/PublicationsDetail.aspx?ID=z9Gur9jZz0k=&t=1

# The DNNAM architecture

In this work, we propose a novel deep neural network-based attention model (DNNAM) architecture, which comprises synchronous dual attention modules (SDAM) and residual modules to recognise structural components. These modules help us to extract local discriminative features from structural compo- nent images and classify different categories of bridge components. These innovative modules are constructed at the contextual level of information encoding across spatial and channel dimensions. Experimental results and ablation studies on benchmarking bridge components and semantic augmented datasets show that our pro- posed architecture outperforms current state-of-the-art methodologies for structural component recognition.

Diagram of the DNNAM architecture:
![DNNAM Architecture](figures/Architecture.png)
