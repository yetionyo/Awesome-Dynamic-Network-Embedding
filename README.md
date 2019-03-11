# Awesome-Dynamic-Network-Embedding
This repository collects a lot of papers related to mining dynamic/temporal patterns in the network.

Contributed by [Zhining Liu](https://scholar.google.com/citations?user=Kk0-z5IAAAAJ&hl=zh-CN), [Dawei Zhou](http://www.public.asu.edu/~dzhou23/).

## Papers

[//]: #2019
- **3D Graph Convolutional Networks with Temporal Graphs: A Spatial Information Free Framework For Traffic Forecasting.**
  *Bing Yu, Mengzhang Li, Jiyong Zhang, Zhanxing Zhu.* Arxiv 2019. [[Paper]](https://arxiv.org/abs/1903.00919)
    - Summary: construct the graph based the similarity between each pair of roads and a fully 3D graph convolution operator is proposed.

[//]: #2018
- **Diffusion Convolutional Recurrent Neural Network: Data-Driven Traffic Forecasting.**
  *Yaguang Li, Rose Yu, Cyrus Shahabi, Yan Liu.* ICLR 2018. [[Paper]](https://arxiv.org/abs/1707.01926)[[Code]](https://github.com/liyaguang/DCRNN)
    - Summary: apply the bidirectional diffusion convolution on the directed traffic graph to model spatial information and extract temporal dynamics using gated recurrent units (GRU).

- **Dynamic Network Embedding by Modeling Triadic Closure Process.**
  *Lekui Zhou,Yang Yang, Xiang Ren, Fei Wu, Yueting Zhuang.* AAAI 2018. [[Paper]](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16572)[[Code]](https://github.com/luckiezhou/DynamicTriad)
    - Summary: model how a closed triad from an open triad via triadic closure process.

- **Embedding Temporal Network via Neighborhood Formation.** 
  *Yuan Zuo, Guannan Liu, Hao Lin, Jia Guo, Xiaoqian Hu, Junjie Wu.* KDD 2018. [[Paper]](https://zuoyuan.github.io/files/htne_kdd18.pdf)[[Code]](http://zuoyuan.github.io/files/htne.zip)
    - Summary: use Hawkes Process to model the 1st-order neighborhood formation sequence.

- **Spatio-Temporal Graph Convolutional Networks: A Deep Learning Framework for Traffic Forecasting.**
  *Yu, Bing, Haoteng Yin, and Zhanxing Zhu.* IJCAI 2018. [[Paper]](https://arxiv.org/abs/1709.04875)[[Code]](https://github.com/VeritasYin/STGCN_IJCAI-18)
    - Summary: graph convolution on spatial domain and 1-D convolution along time axis.

[//]: #2017

[//]: #2016
- **Scalable Link Prediction in Dynamic Networks via Non-Negative Matrix Factorization.**
  *Linhong Zhu, Dong Guo, Junming Yin, Greg Ver Steeg, Aram Galstyan.* TKDE 2016. [[Paper]](https://arxiv.org/abs/1411.3675)[[Code]](https://github.com/linhongseba/Temporal-Network-Embedding)
  - Summary: decompose the adjacency matrix of each timestamp to generate node embeddings and add the temporal smoothness over the node embeddings of consecutive timestamps.