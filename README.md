# Awesome-Dynamic-Network-Embedding
This repository collects a lot of papers related to mining dynamic/temporal patterns in the network.

Contributed by [Zhining Liu](https://scholar.google.com/citations?user=Kk0-z5IAAAAJ&hl=zh-CN), [Dawei Zhou](http://www.public.asu.edu/~dzhou23/).

## Papers

[//]: #2019
- **Gated Residual Recurrent Graph Neural Networks for Traffic Prediction.**
 *Chen Cen, Li Kenli, Teo Sin, Zou Xiaofeng, Wang Jie, Zeng Zeng.* AAAI 2019. [[Paper]](https://oar.a-star.edu.sg/jspui/handle/123456789/3020)
  - Summary: diffusion convolutional with different scales of inputs.

- **EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs.**
  *Aldo Pareja, Giacomo Domeniconi, Jie Chen, Tengfei Ma, Toyotaro Suzumura, Hiroki Kanezashi, Tim Kaler, Charles E. Leisersen.* Arxiv 2019. [[Paper]](https://arxiv.org/abs/1902.10191)
  - Summary: integrate the GCN layer and GRU into one module, where $W_t^{(l)}= \text{GRU}(H_t^{(l)},W_{t-1}^{(l)})$ and $H_t^{l+1}=\text{GCONV}(A_t,H_t^{(l)},W_t^{(l)})$, i.e., node embeddings $H_t^{(l)}$ as the GRU input and the weight matrix $W_t^{(l)}$ as the (new) GRU hidden state.

- **3D Graph Convolutional Networks with Temporal Graphs: A Spatial Information Free Framework For Traffic Forecasting.**
  *Bing Yu, Mengzhang Li, Jiyong Zhang, Zhanxing Zhu.* Arxiv 2019. [[Paper]](https://arxiv.org/abs/1903.00919)
  - Summary: construct the graph based the similarity between each pair of roads and a fully 3D graph convolution operator is proposed.

[//]: #2018
- **Continuous-Time Dynamic Network Embeddings.**
  *Giang Hoang Nguyen, John Boaz Lee, Ryan A. Rossi, Nesreen K. Ahmed, Eunyee Koh, Sungchul Kim.* WWW 2018. [[Paper]](https://dl.acm.org/citation.cfm?id=3184558.3191526)
  - Summary: random walks are generated with the constraint of time order and time closeness (how to select the start is also discussed).
    
- **NetWalk: A Flexible Deep Embedding Approach for Anomaly Detection in Dynamic Networks.**
  *Wenchao Yu, Wei Cheng, Charu Aggarwal, Kai Zhang, Haifeng Chen, Wei Wang.* KDD 2018. [[Paper]](https://www.kdd.org/kdd2018/accepted-papers/view/netwalk-a-flexible-deep-embedding-approach-for-anomaly-detection-in-dynamic)[[Code]](https://github.com/chengw07/NetWalk)
  - Summary: maintain a list of random walks and update the list with newly arrived network objects, then update the node/edge embeddings in a incremental online way.
  
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
- **Structured Sequence Modeling with Graph Convolutional Recurrent Networks.**
  *Youngjoo Seo, Michaël Defferrard, Pierre Vandergheynst, Xavier Bresson.* Arxiv 2016. [[Paper]](https://arxiv.org/abs/1612.07659)
  - Summary: two methods to combine RNN with CNN: (1) graph signals firstly are processed by GCN and then use RNN to extract temporal dynamics; (2) replace the $W\times x$ in the RNN with the graph convolution $W*_Gx$.

- **Scalable Link Prediction in Dynamic Networks via Non-Negative Matrix Factorization.**
  *Linhong Zhu, Dong Guo, Junming Yin, Greg Ver Steeg, Aram Galstyan.* TKDE 2016. [[Paper]](https://arxiv.org/abs/1411.3675)[[Code]](https://github.com/linhongseba/Temporal-Network-Embedding)
  - Summary: decompose the adjacency matrix of each timestamp to generate node embeddings and add the temporal smoothness over the node embeddings of consecutive timestamps.
