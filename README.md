# Graph Sanitation and XAI Paper Collections
### Editor: Yulin Zhu
This collection will includes the image/graph sanitation and denoising methods on social networks. And also some general ideas that related.  

Contents:
- XAI on graphs
- XAI on images and others
- Data sanitization 

## XAI on graphs
### Counterfactual explanation on graphs
| Year | Paper names | Venue | Link | Issue |
| ------ | ------ | ------ | ------ | ------ | 
| 2019 | GNNExplainer: Generating Explanations for Graph Neural Networks | NIPS | https://arxiv.org/abs/1903.03894?context=cs | mutual information loss + edge mask|
| 2020 | Parameterized Explainer for Graph Neural Network | NIPS | https://arxiv.org/pdf/2011.04573.pdf | reparametrization trick + binary concrete distribution |
| 2021 | Generative Causal Explanations for Graph Neural Networks | ICML | https://arxiv.org/abs/2104.06643| Granger causality |
| 2021 | CF-GNNExplainer: Counterfactual Explanations for Graph Neural Networks | ICML Workshop |https://a-lucic.github.io/talks/ICML_HILL_cfgnn.pdf | Causal + edge mask |
| 2021 | Counterfactual Graph Learning for Link Prediction |Arxiv | https://arxiv.org/pdf/2106.02172.pdf | joint training: factual links + counterfactual links |

## XAI on images and others
## Data sanitization

## Image
## Graph
### Graph Denoising

| Year | Paper names | Venue | Link | Issue |
| ------ | ------ | ------ | ------ | ------ | 
| 2021 | Mask-GVAE: Blind Denoising Graphs via Partition | WWW | https://arxiv.org/pdf/2102.04228.pdf | mincut loss + masked gvae |
| 2021 | Learning to drop: robust graph neural network via topological denoising | WSDM | https://dl.acm.org/doi/abs/10.1145/3437963.3441734 | learn denoising network to drop task-irrelevant edges |

### Graph Sanitation

| Type | Paper names | Venue |Link | Issue |
| ------ | ------ | ------| ------| ------|
| 2019 |Adversarial Examples for Graph Data: Deep Insights into Attack and Defense | IJCAI | https://www.ijcai.org/proceedings/2019/0669.pdf | GCN-Jaccard |
| 2020 |All You Need Is Low (Rank): Defending Against Adversarial Attacks on Graphs | WSDM | https://dl.acm.org/doi/10.1145/3336191.3371789 | GCN-SVD |
