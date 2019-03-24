# Awesome-Dynamic-Network-Embedding
This repository collects a lot of papers related to mining dynamic/temporal patterns in the network.

Contributed by [Zhining Liu](https://scholar.google.com/citations?user=Kk0-z5IAAAAJ&hl=zh-CN), [Dawei Zhou](http://www.public.asu.edu/~dzhou23/).

## Papers

[//]: #2019
- **Predicting Citywide Crowd Flows in Irregular Regions Using Multi-View Graph Convolutional Networks.**
  *Junkai Sun, Junbo Zhang, Qiaofei Li, Xiuwen Yi, Yu Zheng.* Arxiv 2019. [[Paper]](https://arxiv.org/abs/1903.07789)
  - Summary: different scales of data are input to GCN and global information (e.g., weather and day of the week) are fed to fully-connected neural network, then a module of multi-view fusion based the gating mechanism is designed to combine two kinds of information to generate the final predictions.

- **Revisiting Spatial-Temporal Similarity: A Deep Learning Framework for Traffic Prediction.**
  *Huaxiu Yao, Xianfeng Tang, Hua Wei, Guanjie Zheng, Zhenhui Li.* AAAI 2019. [[Paper]](https://arxiv.org/abs/1803.01254)[[Code]](https://github.com/tangxianfeng/STDN)
  - Summary: two intriguing assumptions are proposed: (1) the spatial dependencies between locations are also evolving w.r.t the time; (2) the temporal dependency is not strictly periodic due to its dynamic temporal shifting, and the gating mechanism and attention mechanism are introduced to solve the aforementioned problems.

- **Attention Based Spatial-Temporal Graph Convolutional Networks for Traffic Flow Forecasting.**
  *Shengnan Guo, Youfang Lin, Ning Feng, Chao Song, Huaiyu Wan.* AAAI 2019. [[Paper]](https://github.com/Davidham3/ASTGCN/blob/master/2019%20AAAI_Attention%20Based%20Spatial-Temporal%20Graph%20Convolutional%20Networks%20for%20Traffic%20Flow%20Forecasting.pdf)[[Code]](https://github.com/Davidham3/ASTGCN)
  - Summary: graph convolutions along the spatial dimension and a standard convolution along the temporal dimension with spatial-temporal attention and different period components as inputs.

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
- **dyngraph2vec: Capturing Network Dynamics using Dynamic Graph Representation Learning.**
  *Palash Goyal, Sujit Rokka Chhetri, Arquimedes Canedo.* Arxiv 2018. [[Paper]](https://arxiv.org/abs/1809.02657)[[Code]](https://github.com/palash1992/DynamicGEM)
  - Summary: under the framework of encoder-and-decoder, use the neighborhood vector set (collect all neighborhood vector of different timestamps) of each node as input and the reconstruction loss as the objective function.

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
  - Summary: two methods to combine RNN with CNN: (1) graph signals firstly are processed by GCN and then use RNN to extract temporal dynamics; (2) replace the dense layer (W·x) in the RNN with the graph convolution (W_g*x).

- **Scalable Link Prediction in Dynamic Networks via Non-Negative Matrix Factorization.**
  *Linhong Zhu, Dong Guo, Junming Yin, Greg Ver Steeg, Aram Galstyan.* TKDE 2016. [[Paper]](https://arxiv.org/abs/1411.3675)[[Code]](https://github.com/linhongseba/Temporal-Network-Embedding)
  - Summary: decompose the adjacency matrix of each timestamp to generate node embeddings and add the temporal smoothness over the node embeddings of consecutive timestamps.
