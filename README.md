# DCCNet-Pytorch
Implementation of “Dynamic Context Correspondence Network for Semantic Alignment” (ICCV 2019)

# Introduction
Establishing semantic correspondence is a core problem in computer vision and remains challenging due to large intra-class variations and lack of annotated data. In this paper, we aim to incorporate global semantic context in a flexible manner to overcome the limitations of prior work that relies on local semantic representations. To this end, we first propose a context-aware semantic representation that incorporates spatial layout for robust matching against local ambiguities. We then develop a novel dynamic fusion strategy based on attention mechanism to weave the advantages of both local and context features by integrating semantic cues from multiple scales. We instantiate our strategy by designing an end-to-end learnable deep network, named as Dynamic Context Correspondence Network (DCCNet). To train the network, we adopt a multi-auxiliary task loss to improve the efficiency of our weakly-supervised learning procedure. Our approach achieves superior or competitive performance over previous methods on several challenging datasets, including PF-Pascal, PF-Willow, and TSS, demonstrating its effectiveness and generality.

# Enviroment
Python 3.5.2
Pytorch 0.3.1
torchvision 0.2.1
