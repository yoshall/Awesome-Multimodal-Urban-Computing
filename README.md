[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# Awesome-Multimodal-Urban-Computing

Welcome to our carefully curated collection of amazing Multimodal Urban Computing models! This repository serves as a valuable addition to our comprehensive survey paper. Rest assured, we are committed to consistently updating it to ensure it remains up-to-date and relevant.

<img src="https://github.com/yoshall/Awesome-Multimodal-Urban-Computing/blob/main/intro.png" width = "900" align=center>

By [Citymind LAB](https://citymind.top), [HKUST(GZ)](https://www.hkust-gz.edu.cn/). If there are any areas, papers, and datasets I missed, please let me know!

Check out our comprehsensive tutorial paper:
> **Deep Learning for Cross-Domain Data Fusion in Urban Computing: Taxonomy, Advances, and Outlook.** Xingchen Zou, Yibo Yan, Xixuan Hao, Yuehong Hu, Haomin Wen, Erdong Liu, Junbo Zhang, Yong Li, Tianrui Li, Yu Zheng, Yuxuan Liang. [[Link](https://arxiv.org/abs/2402.19348)]

> **<p align="justify"> Abstract:** *As cities continue to burgeon, Urban Computing emerges as a pivotal discipline for sustainable development by harnessing the power of cross-domain data fusion from diverse sources (e.g., traffic, geographical, social network, and environmental data) and modalities (e.g., spatio-temporal, visual, and textual modalities). Recently, we are witnessing a rising trend that utilizes various deep-learning methods to facilitate cross-domain data fusion in smart cities. To this end, we propose the first survey that systematically reviews the latest advancements in deep learning-based data fusion methods tailored for urban computing. Specifically, we first delve into data perspective to comprehend the role of each modality and data source. Secondly, we classify the methodology into four primary categories: feature-based, alignment-based, contrast-based, and generation-based fusion methods. Thirdly, we further categorize multi-modal urban applications into seven types: urban planning, transportation, economy, public safety, society, environment, and energy. Compared with previous surveys, we focus more on the synergy of deep learning methods with urbancomputing applications. Furthermore, we shed light on the interplay between Large Language Models (LLMs) and urban computing, postulating future research directions that could revolutionize the field. We firmly believe that the taxonomy, progress, and prospects delineated in our survey stand poised to significantly enrich the research community.* </p>


#### We strongly encourage authors of relevant works to make a pull request and add their paper's information [[here](TBC)].

____

## News
```
- 2024.01.31: Latest update of this paper list.

```

## Citation

If you find our work useful in your research, please consider citing:
```
@misc{zou2024deep,
      title={Deep Learning for Cross-Domain Data Fusion in Urban Computing: Taxonomy, Advances, and Outlook}, 
      author={Xingchen Zou and Yibo Yan and Xixuan Hao and Yuehong Hu and Haomin Wen and Erdong Liu and Junbo Zhang and Yong Li and Tianrui Li and Yu Zheng and Yuxuan Liang},
      year={2024},
      eprint={2402.19348},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

## Contents

- [Related Surveys](#related-surveys)
- [Taxonomy Framework](#taxonomy-framework) 
- [Data Fusion Methods](#data-fusion-methods)
- [Taxonomy and summary of open-sourced dataset](#Taxonomy-and-summary-of-open-sourced-dataset)
- [Highly Related Paper List](#highly-related-paper-list)

## Related Surveys

- Methodologies for cross-domain data fusion: An overview [[paper](https://ieeexplore.ieee.org/abstract/document/7230259?casa_token=-TMtVQnUBhUAAAAA:QAoxfypjcmMDhwJIoP4zncJFsYyN3Pq1qAy7_Wbn0qQhp52ZDVRLHYbFAtJOEkYThGBeZmc88n1gKTQ)] <br>  *IEEE Transactions on Big Data (2015)*
- Deep learning for spatio-temporal data mining: A survey [[paper](https://ieeexplore.ieee.org/abstract/document/9204396?casa_token=gg2OJPRv3OYAAAAA:5JIp6glMuVNfs-ZVRiQW---yazDzmenL_cD1ng54NN1zwKqDs39tA8akus7mRvVlBLznm0YCFaNS270)] <br>  *IEEE Transactions on Knowledge and Data Engineering (2020)*
- Urban big data fusion based on deep learning: An overview [[paper](https://www.sciencedirect.com/science/article/pii/S1566253519301393)] <br>  *Elsevier Information Fusion (2020)*
- Urban flow prediction from spatiotemporal data using machine learning: A survey [[paper](https://www.sciencedirect.com/science/article/pii/S1566253519303094)] <br>  *Elsevier Information Fusion (2020)*
- A survey of traffic prediction: from spatio-temporal data to intelligent transportation [[paper](https://link.springer.com/article/10.1007/s41019-020-00151-z)] <br>  *Springer Data Science and Engineering (2021)*
- Multi-feature, multi-modal, and multi-source social event detection: A comprehensive survey [[paper](https://www.sciencedirect.com/science/article/pii/S1566253521002220)] <br>  *Elsevier Information Fusion (2022)*
- Generative adversarial networks for spatio-temporal data: A survey [[paper](https://dl.acm.org/doi/abs/10.1145/3474838?casa_token=teiphFvDYXUAAAAA:pVfquKjBsT3XrQVhVhZxDzBRuVxnoaW5Ss8erwqOCY1frqckDPTxXDxoQQYkkSqiMcmzMEXoWBqrYK_S)] <br>  *ACM Transactions on Intelligent Systems and Technology (2022)*
- Beyond just vision: A review on self-supervised representation learning on multimodal and temporal data [[paper](https://arxiv.org/abs/2206.02353)] <br>  *arXiv preprint (2022)*


## Taxonomy Framework

This survey is structured along three dimensions: 
+ data in cross-domain fusion in urban computing
+ modality fusion methods
+ applications based on data fusion.
<img src="https://github.com/yoshall/Awesome-Multimodal-Urban-Computing/blob/main/taxonomy_framework.png" width = "800" align=center>

## Data Fusion Methods

The summary of deep learning-based cross-domain data fusion models in urban computing. 

*Notice that method names are assigned based on original reference model names if available; otherwise, they are named after the first authors.*

<table>
    <tr>
        <th>Category</th>
        <th>Method</th>
        <th>Application</th>
        <th>Institution</th>
        <th>Year</th>
    </tr>
    <tr>
        <td rowspan="30"><strong><em>Feature Based Data Fusion</em></strong></td>
        <td>DeepST <a href="https://dl.acm.org/doi/abs/10.1145/2996913.2997016?casa_token=_Jllet6u2ycAAAAA:Vy0yBHwpqaUzveBMWJRl3x6EXqRfkM1SQ6OqDqUEsN4WCeyVR2wGNYPuDuXhXngE_HYlj_WugEgfyDk">[DNN-based prediction model for spatio-temporal data]</a></td>
        <td>Transportation</td>
        <td>Microsoft</td>
        <td>2016</td>
    </tr>
    <tr>
        <td>ST-ResNet <a href="https://www.sciencedirect.com/science/article/pii/S0004370218300973">[Predicting citywide crowd flows using deep spatio-temporal residual networks]</a></td>
        <td>Transportation</td>
        <td>Microsoft</td>
        <td>2018</td>
    </tr>
    <tr>
        <td>ST-MetaNet+ <a href="https://ieeexplore.ieee.org/abstract/document/9096591?casa_token=ijqIbcMRQVwAAAAA:Gt8bwXyrEaiJgqpRHBRVWQfsmWPhzQXbYHVTmUbM2jTqwVKv7t9c9SSjqx7lIO_szB2Fsv6ZYBCZbw">[Spatio-temporal meta learning for urban traffic prediction]</a></td>
        <td>Transportation</td>
        <td>JD Research</td>
        <td>2020</td>
    </tr>
    <tr>
        <td>DeepCrime <a href="https://dl.acm.org/doi/abs/10.1145/3269206.3271793">[DeepCrime: Attentive hierarchical recurrent networks for crime prediction]</a></td>
        <td>Social</td>
        <td>JD Research</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>STUKG <a href="https://dl.acm.org/doi/abs/10.1145/3494993?casa_token=Ec8UzKCeygsAAAAA:MDByKbtaJ7Et2zOQc6DH4e2QplTsuEyFXUmGZMXIrhpJxXZvucWRptgvQG7CxYYDeZyssM7XIpJVqqE">[Spatio-temporal urban knowledge graph enabled mobility prediction]</a></td>
        <td>Transportation</td>
        <td>THU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>DeepSTN+ <a href="https://ojs.aaai.org/index.php/AAAI/article/view/3892">[Deepstn+: Context-aware spatial-temporal neural network for crowd flow prediction in metropolis]</a></td>
        <td>Transportation</td>
        <td>THU</td>
        <td>2019</td>
    </tr>
    <tr>
        <td>DeepTP <a href="https://ieeexplore.ieee.org/abstract/document/9458698?casa_token=5ncUMsqZWyUAAAAA:JjxJwWcT6YcBkrJaXzvLmTplU69stDA6BYxp-ptvIiRenNq3nSg3G7xYKuLSzLs0Gl5h7gi_mG9FvA">[An effective joint prediction model for travel demands and traffic flows]</a></td>
        <td>Transportation</td>
        <td>THU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Rod revenue<a href="https://ieeexplore.ieee.org/abstract/document/8733999?casa_token=1jir5pSYyG0AAAAA:HRF2TP71TjcegnudXQwIaG2XaPKJ8gc4hMjU4G4OIHH-_pWKh9nfFFWc-97gmQ9tbh90HwcqcQiQ0A">[Rod-revenue: Seeking strategies analysis and revenue prediction in ride-on-demand service using multi-source urban data]</a></td>
        <td>Transportation</td>
        <td>BUAA</td>
        <td>2019</td>
    </tr>
    <tr>
        <td>Photo2Trip <a href="https://dl.acm.org/doi/abs/10.1145/3123266.3123336?casa_token=UtTlSNFAsj8AAAAA:RuSzJLjD2ZVOEMdfgSbEquuvvIuDPgQDnsr_ZLk6tMTacGuE65XlxxIrc8r20QJ6i6ZSUOVYsKnDpss">[Photo2Trip: Exploiting visual contents in geo-tagged photos for personalized tour recommendation]</a></td>
        <td>Transportation</td>
        <td>USTC/RU</td>
        <td>2017</td>
    </tr>
    <tr>
        <td>ST-SHN <a href="https://arxiv.org/abs/2201.02435">[Spatial-Temporal Sequential Hypergraph Network for Crime Prediction with Dynamic Multiplex Relation Learning]</a></td>
        <td>Public Safety</td>
        <td>SCUT/HKU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Huang et al. <a href="https://www.sciencedirect.com/science/article/abs/pii/S0198971523001060">[Comprehensive urban space representation with varying numbers of street-level images]</a></td>
        <td>Urban planning</td>
        <td>PKU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>Liang et al. <a href="https://dl.acm.org/doi/abs/10.1145/3442381.3449792">[Fine-Grained Urban Flow Prediction]</a></td>
        <td>Transportation</td>
        <td>NUS</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Balsebre et al. <a href="https://dl.acm.org/doi/abs/10.1145/3485447.3512026?casa_token=TcjgmEYZsLwAAAAA:IJw5q3FT8czLrqBcABIX_hyftUKBQi5VLX-BR933ERmvG_igo-K3HTubFn_CHMkBTn-L7Po0gIzFW_s">[Geospatial Entity Resolution]</a></td>
        <td>Urban Planning</td>
        <td>NTU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>Ruan et al. <a href="https://dl.acm.org/doi/abs/10.1145/3534678.3539027?casa_token=l12aHjEUcmYAAAAA:-YFMXUW7HizB9W3ZVPQT68AIwVMU0b7Ub1atgQSCwu-hANKaIjgNyF9zmCLSMj_OJKeUpC7kYKRCGS4">[Service Time Prediction for Delivery Tasks via Spatial Meta-Learning]</a></td>
        <td>Transportation</td>
        <td>NTU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>Liu et al. <a href="https://dl.acm.org/doi/full/10.1145/3568683?casa_token=sx9zdRtM96gAAAAA%3AAT6yrSzEHY5zOdfppjBT-DGasK1oTtFjp6YG9YvR65g6gsvftPoNZwIomxEDLJFXQugNJZzaF2kMSsQ">[Characterizing and Forecasting Urban Vibrancy Evolution: A Multi-View Graph Mining Perspective]</a></td>
        <td>Economy</td>
        <td>HKUST(GZ)</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>PANDA <a href="https://link.springer.com/article/10.1007/s42486-022-00095-5">[PANDA: predicting road risks after natural disasters leveraging heterogeneous urban data]</a></td>
        <td>Public Safety</td>
        <td>XMU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>UVLens <a href="https://dl.acm.org/doi/abs/10.1145/3463495?casa_token=FXS3CKSYEOYAAAAA:9zyC-QJQ1cltV5WC_s1SVbwQdxtXX9TbyFf5-cIXlPkhD4fU78GpQgDj7VEpZhg19vQ0jzjQKmfatxc">[Urban Village Boundary Identification and Population Estimation Leveraging Open Government Data]</a></td>
        <td>Urban Planning</td>
        <td>XMU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td><a href="https://link.springer.com/article/10.1007/s11704-017-6464-3">[Integrating GPS trajectory and topics from Twitter stream for human mobility estimation]</a></td>
        <td>Transportation</td>
        <td>SUSTech</td>
        <td>2019</td>
    </tr>
    <tr>
        <td>NodeSense2Vec <a href="https://ieeexplore.ieee.org/abstract/document/9672072?casa_token=yCr8VJMcxgIAAAAA:MF5hGc70fexPrvJVq4v_U-ltFbAx_oqbmbtWUMRoH-GAz82rLnmjrCx8hIYKGM6AGQTaTdFZ1JTB_A">[Spatiotemporal Context-Aware Network Embedding for Heterogeneous Urban Mobility Data]</a></td>
        <td>Social</td>
        <td>UCF</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Liu et al. <a href="https://dl.acm.org/doi/full/10.1145/3568683?casa_token=ZEtTxOhR8awAAAAA%3A_Xr6B-JkoEKDnY6rx-ykQ8IFTaSWG9xJNekc4edC6vjO4n8mlBH88BnpzWieRQtrM_WACQJxCkw2Fac">[Characterizing and Forecasting Urban Vibrancy Evolution: A Multi-View Graph Mining Perspective]</a></td>
        <td>Urban Planning</td>
        <td>UCF</td>
        <td>2020</td>
    </tr>
    <tr>
        <td>Fu et al. <a href="https://ojs.aaai.org/index.php/AAAI/article/view/3879">[Efficient region embedding with multi-view spatial networks: A perspective of locality-constrained spatial autocorrelations]</a></td>
        <td>General</td>
        <td>UCF</td>
        <td>2019</td>
    </tr>
    <tr>
        <td>Liu et al. <a href="https://ieeexplore.ieee.org/abstract/document/9050875?casa_token=YPSDqpHkFikAAAAA:b4SM0qjUjl0kUhiLViCigGhK47DPVZ2po4jHmrj-9t_0NQ_i-js7QE_yFixN38WUEtDnGVRztGs6fg">[Spatiotemporal Activity Modeling via Hierarchical Cross-Modal Embedding]</a></td>
        <td>Social</td>
        <td>Gatech</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>Yuan et al. <a href="https://ieeexplore.ieee.org/abstract/document/9458698?casa_token=5ncUMsqZWyUAAAAA:JjxJwWcT6YcBkrJaXzvLmTplU69stDA6BYxp-ptvIiRenNq3nSg3G7xYKuLSzLs0Gl5h7gi_mG9FvA">[An effective joint prediction model for travel demands and traffic flows]</a></td>
        <td>Transportation</td>
        <td>RMIT</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Bai et al. <a href="https://dl.acm.org/doi/pdf/10.1145/3511808.3557370">[Spatio-temporal graph convolutional and recurrent networks for citywide passenger demand prediction]</a></td>
        <td>Transportation</td>
        <td>Shanghai AI Lab</td>
        <td>2019</td>
    </tr>
    <tr>
        <td>Ke et. al <a href="https://arxiv.org/pdf/2011.05602">[Joint predictions of multi-modal ride-hailing demands: A deep multi-task multi-graph learning-based approach]</a></td>
        <td>Transportation</td>
        <td>Alibaba</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Guo et al. <a href="https://ieeexplore.ieee.org/abstract/document/9238459?casa_token=VxAEiwiSInAAAAAA:_NM3ge3f3pliOAsbipKBQPn1Z9-PMxzXJSYy5PHYAaaqkVWcEzGkyx_l_DsdaC83CmQPVwevvj-Byw">[A Force-Directed Approach to Seeking Route Recommendation in Ride-on-Demand Service Using Multi-Source Urban Data]</a></td>
        <td>Transportation</td>
        <td>Alibaba</td>
        <td>2019</td>
    </tr>
    <tr>
        <td>Yao et al.<a href="https://ojs.aaai.org/index.php/AAAI/article/view/11836">[Deep multi-view spatial-temporal network for taxi demand prediction]</a></td>
        <td>Transportation</td>
        <td>PSU</td>
        <td>2018</td>
    </tr>
    <tr>
        <td>Gao et al. <a href="https://www.sciencedirect.com/science/article/abs/pii/S0020025522004819">[Contextual spatio-temporal graph representation learning for reinforced human mobility mining]</a></td>
        <td>Transportation</td>
        <td>SWJTU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>DeepMob <a href="https://dl.acm.org/doi/abs/10.1145/3057280?casa_token=-MQz6aOv_WgAAAAA:dfBZ8q-WljFjUH5OFWtFkykguS5Q2bMQsNrcZPUMrjuQNw16eOdSk83I6DTHlERoTL8VTXKSf-ZerdQ">[Learning Deep Knowledge of Human Emergency Behavior and Mobility from Big and Heterogeneous Data]</a></td>
        <td>Public Safety</td>
        <td>SUSTech</td>
        <td>2017</td>
    </tr>
    <tr>
        <td>Geng<a href="https://ojs.aaai.org/index.php/AAAI/article/view/4247">[Spatiotemporal multi-graph convolution network for ride-hailing demand forecasting]</a></td>
        <td>Transportation</td>
        <td>HKUST</td>
        <td>2019</td>
    </tr>
    <tr>
        <td rowspan="13"><strong><em>Alignment Based Data Fusion</em></strong></td>
        <td><a href="https://dl.acm.org/doi/abs/10.1145/3485447.3512149">[Beyond the First Law of Geography: Learning Representations of Satellite Imagery by Leveraging Point-of-Interests]</a></td>
        <td>General</td>
        <td>THU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>Zhang et al. <a href="https://fi.ee.tsinghua.edu.cn/public/publications/301ad6d8-92b8-11eb-96bc-0242ac120003.pdf">[Multi-View Joint Graph Representation Learning for Urban Region Embedding]</a></td>
        <td>General</td>
        <td>THU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Yuan et al. <a href="your_citation_link">[An effective joint prediction model for travel demands and traffic flows]</a></td>
        <td>Transportation</td>
        <td>THU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Yin et al. <a href="https://ieeexplore.ieee.org/abstract/document/9458698?casa_token=PuqlRYsABxAAAAAA:xTdwTjLwlWzZvF5BShhkLvAlzE15AB9lwySluVlXYeNAlxKFC6aUibBFsvUYYDQlBaEGalw5zoObvQ">[yinMultitaskLearningFramework2020a]</a></td>
        <td>Urban Planning</td>
        <td>NUS</td>
        <td>2020</td>
    </tr>
    <tr>
        <td>GSNet <a href="https://ojs.aaai.org/index.php/AAAI/article/view/16566">[GSNet: Learning Spatial-Temporal Correlations from Geographical and Semantic Aspects for Traffic Accident Risk Forecasting
]</a></td>
        <td>Public Safety</td>
        <td>BJTU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Hashem et al. <a href="https://www.mdpi.com/2071-1050/15/5/3916">[Urban Computing for Sustainable Smart Cities: Recent Advances, Taxonomy, and Open Research Challenges]</a></td>
        <td>General</td>
        <td>NTU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>TrajGAT <a href="https://dl.acm.org/doi/abs/10.1145/3534678.3539358">[Trajgat: A graph-based long-term dependency modeling approach for trajectory similarity computation]</a></td>
        <td>Transportation</td>
        <td>NTU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>RADAR <a href="https://dl.acm.org/doi/abs/10.1145/3161159?casa_token=nvO52WgM2ZkAAAAA:_9G52wzJNs8pTwEcYH-H4rflNZG3u_8OIFJOMq-Wyw5wswIIaUwk_MZdfTZf0JPrnkt-ZhQTgeakOQk">[RADAR: Road Obstacle Identification for Disaster Response Leveraging Cross-Domain Urban Data]</a></td>
        <td>General</td>
        <td>XMU</td>
        <td>2018</td>
    </tr>
    <tr>
        <td>Wang et al. <a href="https://ieeexplore.ieee.org/abstract/document/9652050?casa_token=rn1XylthWVMAAAAA:kjVgIM9mtuyxMa26yQ_zfIM3wquE6xyl6aFwJZ42RM_PbdfGT6kuTvIaEqk9hY_4YWLvnuHQpLbA_g">[Traffic accident risk prediction via multi-view multi-task spatio-temporal networks]</a></td>
        <td>General</td>
        <td>CSU</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>Ted et al. <a href="https://link.springer.com/article/10.1007/s00778-022-00748-y">[Unified Route Representation Learning for Multi-Modal Transportation Recommendation with Spatiotemporal Pre-Training]</a></td>
        <td>Transportation</td>
        <td>RMIT</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>ERNIE-GeoL <a href="https://dl.acm.org/doi/abs/10.1145/3534678.3539021?casa_token=gL8mL0Lz5AMAAAAA:2pHxGWb8f5k8PtQ8awFHUeW9tl9t98eRqmU3eL4e4kRPtKjlgqtadvyp2dHLKyGkJGZM8N9vqyZmZ_U">[A Geography-and-Language Pre-trained Model and its Applications in Baidu Maps]</a></td>
        <td>General</td>
        <td>Baidu</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>SAInf <a href="https://urban-computing.com/pdf/KDD2023_stay.pdf">[SAInf: Stay Area Inference of Vehicles using Surveillance Camera Records]</a></td>
        <td>Transportation</td>
        <td>JD Research</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>Gao et al. <a href="https://www.sciencedirect.com/science/article/abs/pii/S1566253522002287">[Dual-grained human mobility learning for location-aware trip recommendation with spatial–temporal graph knowledge fusion]</a></td>
        <td>Transportation</td>
        <td>SWJTU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td rowspan="8"><strong><em>Contrast Based Data Fusion</em></strong></td>
        <td>KnowCL <a href="https://dl.acm.org/doi/abs/10.1145/3543507.3583876">[Knowledge-infused Contrastive Learning for Urban Imagery-based Socioeconomic Prediction]</a></td>
        <td>Economy</td>
        <td>THU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>Li et al. <a href="https://dl.acm.org/doi/abs/10.1145/3511808.3557153">[Predicting Multi-level Socioeconomic Indicators from Structural Urban Imagery]</a></td>
        <td>Economy</td>
        <td>THU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>MMGR <a href="https://www.sciencedirect.com/science/article/pii/S0924271623001235">[Geographic mapping with unsupervised multi-modal representation learning from VHR images and POIs]</a></td>
        <td>General</td>
        <td>NTU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>ReMVC <a href="https://ieeexplore.ieee.org/abstract/document/9973276/?casa_token=4YaGlNScjNwAAAAA:pMi6gloGOsjEL6AtdY6CCqaOxFj_E6ik0UWEUOVVv_hj1k1f6rOOOUtutJG-LmPkw1tECCzWa_2IBQ">[Region Embedding with Intra and Inter-View Contrastive Learning]</a></td>
        <td>Urban Planning</td>
        <td>NTU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>HMTRL <a href="https://link.springer.com/article/10.1007/s00778-022-00748-y">[Unified route representation learning for multi-modal transportation recommendation with spatiotemporal pre-training]</a></td>
        <td>Transportation</td>
        <td>UCF</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>Mao et al. <a href="Jointly Contrastive Representation Learning on Road Network and Trajectory">[Jointly contrastive representation learning on road network and trajectory]</a></td>
        <td>Transportation</td>
        <td>Shanghai AI Lab</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>UrbanSTC <a href="https://ieeexplore.ieee.org/abstract/document/9864246?casa_token=fLbArl8AbuMAAAAA:YxtQGcPEhkFnfdA7FSB4lF3rQ8QOZ2vaoSO2alvXVndSs-wrpFStGvLvdTfoQQdcCTYdNEehEWkmxQ">[Forecasting fine-grained urban flows via spatio-temporal contrastive self-supervision]</a></td>
        <td>Transportation</td>
        <td>JD Research</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>UrbanCLIP <a href="https://arxiv.org/abs/2310.18340">[When Urban Region Profiling Meets Large Language Models]</a></td>
        <td>General</td>
        <td>HKUST(GZ)</td>
        <td>2023</td>
    </tr>
    <tr>
        <td rowspan="9"><strong><em>Generation Based Data Fusion</em></strong></td>
        <td>SG-GAN <a href="https://ieeexplore.ieee.org/abstract/document/9200630">[An enhanced gan model for automatic satellite-to-map image conversion]</a></td>
        <td>Urban Planning</td>
        <td>NUS</td>
        <td>2020</td>
    </tr>
    <tr>
        <td>ActSTD <a href="https://dl.acm.org/doi/abs/10.1145/3534678.3542671">[Activity trajectory generation via modeling spatiotemporal dynamics]</a></td>
        <td>Transportation</td>
        <td>THU</td>
        <td>2022</td>
    </tr>
    <tr>
        <td>DiffSTG <a href="https://dl.acm.org/doi/abs/10.1145/3589132.3625614?casa_token=e0UhNIJm1vkAAAAA:QSm-ru_XX4j1L3vLGdyuCoB7-W5i577s-Oj7hGiNq4b30uyOhjb_VgrjZn7llT2QVEuqAdXYD7wFOhc">[Diffstg: Probabilistic spatio-temporal graph forecasting with denoising diffusion models]</a></td>
        <td>General</td>
        <td>BJTU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>CP-Route <a href="https://ieeexplore.ieee.org/abstract/document/10225450?casa_token=HlK3IvZc4lgAAAAA:5z4ys4Kwv4fQiewvbexydlFEN4GPCuF1TgZEkChcsWR8Dek2gO7uahAnInfUtu1diEk1HzI8p-HAOw">[Modeling Spatial–Temporal Constraints and Spatial-Transfer Patterns for Couriers’ Package Pick-up Route Prediction]</a></td>
        <td>Transportation</td>
        <td>BJTU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>G2PTL <a href="https://arxiv.org/abs/2304.01559">[G2PTL: A Pre-trained Model for Delivery Address and its Applications in Logistics System]</a></td>
        <td>Transportation</td>
        <td>Cainiao</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>DiffUFlow <a href="https://dl.acm.org/doi/abs/10.1145/3583780.3614842?casa_token=70EI8xajwnQAAAAA:NJsEthSc0GvyPNwhInIIYPf8qeT3pTXsmTd9XopAX9LbkngMhw-26CGtUsG9JOU1Uiy2hsiH7AAOfiI">[DiffUFlow: Robust Fine-grained Urban Flow Inference with Denoising Diffusion Model]</a></td>
        <td>Transportation</td>
        <td>CSU</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>DP-TFI <a href="https://ieeexplore.ieee.org/abstract/document/10096169?casa_token=0L_1VDGADUMAAAAA:KYxU5gEGb8hiE1r4KrVpnmvhJdueSGAAVdAB6zMEpEmljJmqwG_RnN3YWrCVZ8ah3CdvNWpCkh5Tcw">[Diffusion Probabilistic Modeling for Fine-Grained Urban Traffic Flow Inference with Relaxed Structural Constraint]</a></td>
        <td>Transportation</td>
        <td>UEST</td>
        <td>2023</td>
    </tr>
    <tr>
        <td>Wang et al. <a href="https://ieeexplore.ieee.org/abstract/document/9679173?casa_token=qKgtNCihtjgAAAAA:qVVSo6ZpIq2A6DNlzQ-2ry8DNp3tvP5IFm3l_2wPydQwn9bFdjLNh9a8IdfSsR2cE4z_khwNCHNunQ">[Deep Human-guided Conditional Variational Generative Modeling for Automated Urban Planning]</a></td>
        <td>Urban Planning</td>
        <td>UCF</td>
        <td>2021</td>
    </tr>
    <tr>
        <td>MGEO <a href="https://ieeexplore.ieee.org/abstract/document/9679173?casa_token=qKgtNCihtjgAAAAA:qVVSo6ZpIq2A6DNlzQ-2ry8DNp3tvP5IFm3l_2wPydQwn9bFdjLNh9a8IdfSsR2cE4z_khwNCHNunQ">[Deep Human-guided Conditional Variational Generative Modeling for Automated Urban Planning]</a></td>
        <td>General</td>
        <td>Alibaba</td>
        <td>2023</td>
    </tr>
</table>







## Taxonomy and summary of open-sourced dataset

Below is a list of open source datasets categorized by their type and source.



<table>
    <tr>
        <th>Category</th>
        <th>Content</th>
        <th>Format</th>
        <th>Dataset</th>
        <th>Reference</th>
    </tr>
    <tr>
        <td rowspan="3">Geographical Data</td>
        <td>Satellite Image</td>
        <td>Image</td>
        <td>ArcGIS [<a href="https://developers.arcgis.com">Link</a>]<br>PlanetScope [<a href="https://developers.planet.com/docs/data/planetscope/">Link</a>]<br>Google Earth [<a href="https://developers.google.com/maps/documentation/">Link</a>]<br>OpenStreetMap [<a href="https://www.openstreetmap.org/">Link</a>]<br>Baidu Maps [<a href="https://lbsyun.baidu.com">Link</a>]</td>
        <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/3543507.3583876">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3511808.3557153">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3357384.3358001">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3568683">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3534678.3539029?casa_token=jpDze5OKkEwAAAAA:SPOOwnxmokWTICbKEE6hSwQQy7qZVCltzlVnGIB6mHHhnwFwY6GE7aTN06mirTTCKRJ23xvWZNklZIA">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/10184508/10184509/10184898.pdf?casa_token=fpu9Q7eBi6oAAAAA:mwyKc0AgM0wUyAJQ-ZHrTgH0qrifBm0X9f9-0SdrtG_gLpMQvaFmXG_LujHPhB69KqTxzjFPa40LdQ">Paper</a>]</td>
    </tr>
    <tr>
        <td>Street View Image</td>
        <td>Image</td>
        <td>Baidu Map [<a href="https://lbsyun.baidu.com">Link</a>]<br>Google Street [<a href="https://developers.google.com/maps/">Link</a>]<br>Tencent Map [<a href="https://lbs.qq.com/tool/streetview/index.html">Link</a>]</td>
        <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/3543507.3583876">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/4267003/4357939/09171429.pdf?casa_token=xfZHAaczqPkAAAAA:rMZMt2teljSQtU5GX4ZKQ4dV0QuCY_Th2oOAJk7sZ-C9ve89WQfkd23akDPpKWdhCgMwu4qz0_0l5g">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3543507.3583876">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/9565453/9565456/09565523.pdf?casa_token=7bBiwH7j4UYAAAAA:-2GC9z9HnybmvpfvbUjce4uHU43g27XMV-yD8aPyr26qrq0PVUCHZGaPEvPlzh392ezHs3KPpJduVg">Paper</a>]<br>[<a href="https://pdf.sciencedirectassets.com/271803/1-s2.0-S0198971523X00076/1-s2.0-S0198971523001060/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDkaCXVzLWVhc3QtMSJIMEYCIQCUo7xyc0W5I0rFnKw%2FQroN0p2e6ZOCumbR68oyTt%2BiWAIhAIdpupPD05gEWymMaBBdLU8Vd%2BuikW3idcdivZ%2FNmVa5KrsFCML%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBRoMMDU5MDAzNTQ2ODY1IgxMFZdoQoHVSeRCn30qjwUjH%2FB5ngv3owatNuY4oW%2FzafpNHLQJnz9ofJirUb5lt44Y1%2FrqWrOP7zXICTs8kK8sFQ1lxnIXEiaHBv5ubb7HEECsNFbzRiDLyZwbDsg%2FkLRGQpnadU0z5AnO5xsZp6v2Vralyf%2Bagpz%2FGZIBNy36diNbxiabLUvDMN9lMoYWS9QDgqYaB%2FahFdvW5ZtuZ2R8EVtT%2B7KEtpQQKcZxHCw8RubS9bI5GPbOq16ROMzaejPZ9UtwmxTMorQ7CfMf9TwUCRL23Upda9%2BkrYgaXrQwOcmNvKaqd5xWmBVv4t8uhU9xja5RAw4AiilpAMOm7Lr2H7VenKgvJUdIQCSVFAy6Tncp4pCU06V2HcPCbI5RHJbcqSxhxNnlGwkmPiQyVs95dQI0QLbKrmvIwIracatrZY3DOGWfirUaGwYF4tiE5bQMMz7VHnTmCInpt%2FQWLicki7PX3SrFsySWnGSYfU95uYP4ZtArml3JMuX8td%2FyLC%2BYc6YCtB%2FjWLkn3igK7FIqqaXtxyC1xLPEWrUeyYW3fuLlyTgKRIzmxqjl0b1iYWnVhEOVEoDRScPQurzPglGGxgP2yatx0Nz%2Foz8BUUT3lJbdmZa32S%2B7cvUtMzhopKf6ZQxLV%2Br3NB4IjfcbXIWDQhAuN%2BG1NceQ%2FBJM67ZXxHOipB3i%2BYmCwrvB7%2FT7KneIrue9SX5Bl43rKi7k8h1wPlqNkQJ2gMvERoHD7JqsYaT6imtl6fwRjbsAeJ0lstMnRFcjcWJ%2BLGrrrvrK3MJ0HLmSurZCtV5MAmtIqbAcgkwST1O7rJ%2Fh09wxpp5imZ8IkePG%2B9KSIlTipmtUFiWJOdygb2Jy9BXK5Y5MCfifpvrK4zEDNsiN7GTQhOgXMP7UtqwGOrABzO3%2FM0coToCBo4Z1b166HdxPF1qA8coETa3rnZzH9QCTM%2BGWi7ChVvaN8pXRqJKKGaa3D46saXuFOVR0Hwz2DrcLEmD2VHC93Xvlms4ufFch8r1zY3EyWH4NhdKnDzBua24Q74%2B31oLO3gf0RmqLSgpRvVcsVpfKzkdYwVTjFZoqrKGjDJxaD4Ye4xaZWpRT7pC3ozpbbDhKr29bXfJ0%2FLdQ3%2FP5qhOfqblT1bTlh8c%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231228T170835Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYYZB3GU4E%2F20231228%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=38de3b51a0d433aa783aeb2f76c06c9624a086b549df4d1a981ddbd9603d6a8c&hash=b96208d8e278a8971e918d8b8b4e23806a5db1588d7d15d7c8ce76210fe3cde8&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0198971523001060&tid=spdf-328fa907-39b9-40c5-8c83-099625296fa8&sid=d6ecfe1060df624d694998a-721563592842gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=09015b5c000d565603015e&rr=83cb67fa9e764028&cc=sg">Paper</a>]
</td>
    </tr>
    <tr>
        <td>POIs</td>
        <td>Point Vector</td>
        <td>Tencent Map Service [<a href="https://lbs.qq.com/getPoint/">Link</a>]<br>WeChat POIs [<a href="https://open.weixin.qq.com/">Link</a>]<br>Baidu Map POIs [<a href="https://lbsyun.baidu.com">Link</a>]<br>NYC Open POIs [<a href="https://opendata.cityofnewyork.us/">Link</a>]<br>Foursquare [<a href="https://developer.foursquare.com/docs/checkins/checkins">Link</a>]<br>Wikipedia POIs [<a href="https://www.wikipedia.org">Link</a>]<br>AMap Service [<a href="https://lbs.amap.com">Link</a>]<br>Yelp POIs [<a href="https://www.yelp.com/developers">Link</a>]<br>Dianping.com POIs [<a href="https://api.dianping.com/">Link</a>]<br>Weibo POIs [<a href="https://open.weibo.com/wiki/API">Link</a>]<br>Flickr POIs [<a href="https://www.flickr.com/services/developer/api/">Link</a>]<br>Bing Map POIs [<a href="https://www.bingmapsportal.com">Link</a>]</td>
        <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/3057281">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3534678.3539027?casa_token=M6BJF17VrbUAAAAA:pMlMiEENMqezmhLvRo43yWGY9hTteTAyUkSsxAcFOKc3ksgsaEN0F8vB4qIq5p8ZcAkQ-ZzBuRmn_5E">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3494993?casa_token=k8qucI4Qm1sAAAAA:jhGimQsWcrJY4TFg36hJNgahG_twewRvDGbEKUtYdPvDbKyrtdHnjWMIfwKu83wuSSPnILTgZWu_G88">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3511808.3557153">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3568683?casa_token=vsVt5x7WH2gAAAAA:UncXf3YyCbk0IZN4iTUES68bl24uyGIqpMMQFmNGSftJA79aSP8fZJ5Y4ELNruzvbpVLqE08zu1Yeqo">Paper</a>][<a href="https://ojs.aaai.org/index.php/AAAI/article/download/3894/3772">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3534678.3539021">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/10184508/10184509/10184898.pdf?casa_token=fpu9Q7eBi6oAAAAA:mwyKc0AgM0wUyAJQ-ZHrTgH0qrifBm0X9f9-0SdrtG_gLpMQvaFmXG_LujHPhB69KqTxzjFPa40LdQ">Paper</a>]<br>[<a href="https://ojs.aaai.org/index.php/AAAI/article/view/3892/3770">Paper</a>][<a href="https://ojs.aaai.org/index.php/AAAI/article/view/16566/16373">Paper</a>][<a href="https://www.mdpi.com/2073-4433/13/8/1208/pdf">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09973276.pdf?casa_token=PXnl3rfHyKcAAAAA:QsFwwRBYDW3WGYbjpuW0WG9udNyYCp-Drko6dlXEgOCbIlYJjo5LNzApnNOm4nhc1oj-5B9HeSFjMQ">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09652050.pdf?casa_token=mJwbBnDPiDcAAAAA:XZvJGmg7iJf_iluWfa8Lh9s-BQgV3jQgcY2g0CASVNKn_45mEm8GPw0OCOq67wqPAdhM0jPSbzVYLg">Paper</a>]
<br>[<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09935324.pdf?casa_token=xVvSHMkqBpkAAAAA:SaKQkayYOlI1qAvsKnQlwAD0SNjX9DdOZEW5iozWQ5nU_yotBfQ7qxTCiO2vahDvTGhS4Tj9WiKwDA">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/2983323.2983850?casa_token=bb-z6w58UPYAAAAA:CqDDLatHCxLgt_FiBtcRolikkNxge7x71BVj2t97p3T2a877EoPg_GqgaDaNxfNWPd0qHg2OrIBGauw">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3485447.3512026?casa_token=rg3CeBH5nPwAAAAA:ZfQQDcKMdY52D754eLq5qWkk8UjZAWPGak_JovOe59XGKZR8s_Cco3B80zeD0v-KASKs08XpBWDlQCQ">Paper</a>][<a href="https://ojs.aaai.org/index.php/AAAI/article/download/9191/9050">Paper</a>][<a href="https://www.researchgate.net/profile/Dong-Wang-106/publication/310809063_Exploiting_spatial-temporal_social_constraints_for_localness_inference_using_online_social_media/links/5b20b7180f7e9b0e373f0632/Exploiting-spatial-temporal-social-constraints-for-localness-inference-using-online-social-media.pdf">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3357384.3358001">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3123266.3123336?casa_token=Zy3qKgsnrbEAAAAA:bO8RH_rZZSa04ZP-eLJzHGYVbn9t_4V6GcbCF7nWiWMOTqmGXl9PbW6b21Fcs0bKgCK8y783rr4eE70">Paper</a>]<br>[<a href="https://www.researchgate.net/profile/Weiming-Huang-3/publication/371278390_Geographic_mapping_with_unsupervised_multi-modal_representation_learning_from_VHR_images_and_POIs/links/6569aa153fa26f66f4439837/Geographic-mapping-with-unsupervised-multi-modal-representation-learning-from-VHR-images-and-POIs.pdf">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3485447.3512026?casa_token=PvOvnUpu2GEAAAAA:D7CZeoE2AWxMHnVCwVuz3edeBCA4Vs56bMuPlWrvedpDj64SjusUdVGrU7myffWQtqOzE2OGb1gEqEk">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09075417.pdf?casa_token=j9g9S131VN4AAAAA:K8g4PsIR2SnbccYt0rHRwfh68KM61Ao7QgqW9ZPJ1DVLJqS3KleLZVEoG-tBzsznnGvMLNyhc2fGRQ">Paper</a>
][<a href="https://dl.acm.org/doi/pdf/10.1145/2983323.2983850?casa_token=oOmGrEpkXekAAAAA:DOicJXGJkUkpyY1XMndITibkyPQWhS5Q5Srrrzf7ae-SlA7NAhk71cB71CFuap7M85u67AHPAuu7ALs">Paper</a>
]<br>[<a href="https://ieeexplore.ieee.org/iel7/9671263/9671273/09672072.pdf?casa_token=OvW6930HqE0AAAAA:5xVeow0svfPgzlf9JbnsDLi-VgBgX-o6R_oXcUsm8gZGEZYZj9YsyEUpJ9LAaYPDSPmN6vz6W5Isgw">Paper</a>
][<a href="https://ieeexplore.ieee.org/iel7/8961330/8970627/08970913.pdf?casa_token=dGiJQD6JBGYAAAAA:plHLellxuoJotfKZ2JjsJ1B_d3g1eQzN344gSasgcTU-RvoNnjQD-izNwfLRtRYRC0MFfr04_pYd0w">Paper</a>
]<br>[<a href="https://ieeexplore.ieee.org/iel7/9671263/9671273/09672072.pdf?casa_token=OvW6930HqE0AAAAA:5xVeow0svfPgzlf9JbnsDLi-VgBgX-o6R_oXcUsm8gZGEZYZj9YsyEUpJ9LAaYPDSPmN6vz6W5Isgw">Paper</a>
][<a href="https://dl.acm.org/doi/pdf/10.1145/3340531.3412030?casa_token=20OkNaLMQHEAAAAA:lcH5H3pqDrIznHcenod6VumQdKFBeO4pmiV6FVWOU97TleBepRaO0YDkIj-fHvc1NhX3uQszyBPoF7Q">Paper</a>
][<a href="https://www.sciencedirect.com/science/article/pii/S1566253522002287/pdfft?md5=3971930e8a0215c13f0628777fec924d&pid=1-s2.0-S1566253522002287-main.pdf">Paper</a>]<br>[<a href="https://ieeexplore.ieee.org/iel7/8725877/8731337/08731399.pdf?casa_token=XePczjLegakAAAAA:Pk74Vu7znrMR4gZJ3yZbiFZYHZ7xs7JUebgP92rLj-9vlOMWBgw0j3TF3Y-qA15tsscrPd2a6ShzoA">Paper</a>]<br>[<a href="https://arxiv.org/pdf/2206.00007">Paper</a>]</td>
</tr>

<tr>
    <td rowspan="4">Traffic Data</td>
    <td>Traffic Trajectory</td>
    <td>Spatio-temporal Trajectory</td>
    <td>Shenzhen UCar [<a href="https://bit.ly/2MG47xz">Link</a>]<br>Chicago Transportation [<a href="https://data.cityofchicago.org/">Link</a>]<br>VED [<a href="https://github.com/gsoh/VED">Link</a>]<br>Taxi Shenzhen [<a href="https://github.com/cbdog94/STL">Link</a>]<br>NYC Open Taxi Data [<a href="https://opendata.cityofnewyork.us/how-to/">Link</a>]<br>GeoLife [<a href="http://urban-computing.com/index-893.htm">Link</a>]<br>T-Drive Taxi [<a href="http://urban-computing.com/index-58.htm">Link</a>]<br>DiDi Traffic [<a href="https://outreach.didichuxing.com/research/opendata/">Link</a>]<br>Xiamen Taxi [<a href="https://data.mendeley.com/datasets/6xg39x9vgd/1">Link</a>]<br>Grab-Posisi [<a href="https://goo.su/W3yD5m">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://ieeexplore.ieee.org/iel7/7755/4358975/09238459.pdf?casa_token=57UE6m0t1L4AAAAA:07EKUfKbquI7qsNojbUNLuOQdGbXPCSrZy4Sks_S33wg9G71PrufDENbTNq5Yznc3SI_RijjmPi4eg">Paper</a>]<br>[<a href="https://ojs.aaai.org/index.php/AAAI/article/view/16566/16373">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09652050.pdf?casa_token=eISzhi2pzpgAAAAA:gmISK_pWmvHmvtY_wYhb_59On3L_V_J1meomX4InftHQOirUx6I0VCoFvvLDAdrDXq5-IiCxPK0uUQ">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3357384.3358001">Paper</a>]<br>[<a href="https://api.semanticscholar.org/CorpusID:146120975">Paper</a>][<a href="https://arxiv.org/pdf/2203.08630">Paper</a>]<br>[<a href="https://www.sciencedirect.com/science/article/pii/S0198971523001060/pdfft?md5=c8d1eda96b3ffca6c55ccb9fb21bfdde&pid=1-s2.0-S0198971523001060-main.pdf">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/7929494/7929895/07930067.pdf?casa_token=CkwTn_6Hum0AAAAA:s6A_-IHE7hzxTyEGhpQ01VNYYqw_jeEmw3rCi4jcgDE9yq5swEqH8WXJiigcVR0IJxl-hJ0t3Rxsag">Paper</a>]<br>[<a href="http://fi.ee.tsinghua.edu.cn/public/publications/301ad6d8-92b8-11eb-96bc-0242ac120003.pdf">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09973276.pdf?casa_token=zo4E3xIffU0AAAAA:tHqLRoRpGXmz2KRBUVjqKD5SykH6j2vjvOxobdAPGXCjnVpXMxuA6ufMzvvckfmZcZ-EdHTuwZEYcQ">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3447548.3467337">Paper</a>][<a href="https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=24ccdcba118ff9a72de4840efb848c7c852ef247">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/1526709.1526816">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/1409635.1409677">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/6221037/7389462/07145457.pdf">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/2020408.2020462">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/1869790.1869807">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3292500.3330884">Paper</a>][<a href="https://zheng-kai.com/paper/ijcai_2018_lv.pdf">Paper</a>]<br>[<a href="https://ieeexplore.ieee.org/iel7/9458599/9458600/09458698.pdf">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3465058">Paper</a>][<a href="https://www.sciencedirect.com/science/article/pii/S0950705122013338/pdfft?md5=3671ad5212393d9fdaeb946a418ce05a&pid=1-s2.0-S0950705122013338-main.pdf">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3534678.3539358">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3466687">Paper</a>]<br>[<a href="https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/article/10.1007/s42486-022-00095-5&casa_token=J_dIvLR1XM0AAAAA:s8Gjn1A6Va0OnmWxAfTky1g_DUypkZtGOOoL4UNNpX3IavlMQ56TNaG_EuDxJWCLqg-4BR2UtbM665DVIA">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3463495">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/4267003/4357939/09171429.pdf">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3161159">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3618108">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3366423.3380021">Paper</a>]</td>
</tr>
<tr>
    <td>Traffic Flow</td>
    <td>Spatial-temporal Graph</td>
    <td>California-PEMS [<a href="http://pems.dot.ca.gov">Link</a>]<br>METR-LA [<a href="https://www.metro.net">Link</a>]<br>Large-ST [<a href="https://github.com/liuxu77/LargeST">Link</a>]<br>MobileBJ [<a href="https://github.com/FIBLAB/DeepSTN/issues/4">Link</a>]<br>DiDi (Traffic flows) [<a href="https://outreach.didichuxing.com/research/opendata/">Link</a>]<br>TaxiBJ [<a href="https://goo.su/aQyjTAz">Link</a>]<br>BikeNYC [<a href="https://citibikenyc.com/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/1631272.1631476">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/28/4957013/10269662.pdf">Paper</a>]<br>[<a href="https://www.sciencedirect.com/science/article/pii/S0957417423007832/pdfft?md5=d9128c38443cae0e4e4c01bd64ba5706&pid=1-s2.0-S0957417423007832-main.pdf">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3583780.3615160">Paper</a>]<br>[<a href="https://arxiv.org/pdf/2306.08259">Paper</a>]<br>[<a href="https://ojs.aaai.org/index.php/AAAI/article/view/3892/3770">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3340531.3412030">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/9671263/9671273/09672072.pdf">Paper</a>]
    <br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3442381.3449792">Paper</a>][<a href="https://arxiv.org/pdf/1905.10069">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09864246.pdf">Paper</a>][<a href="http://dx.doi.org/10.1109/TITS.2022.3219626">Paper</a>][<a href="http://fi.ee.tsinghua.edu.cn/public/publications/301ad6d8-92b8-11eb-96bc-0242ac120003.pdf">Paper</a>][<a href="http://dx.doi.org/10.1609/aaai.v33i01.3301906">Paper</a>]<br>[<a href="https://doi.org/10.1609/aaai.v33i01.33011020">Paper</a>][<a href="https://arxiv.org/abs/1905.10069">Paper</a>][<a href="https://doi.org/10.1109/TKDE.2022.3200734">Paper</a>][<a href="http://dx.doi.org/10.1109/TITS.2022.3219626">Paper</a>]</td>
</tr>
<tr>
    <td>Road Network</td>
    <td>Spatial Graph</td>
    <td>OpenStreetMap [<a href="https://www.openstreetmap.org">Link</a>]<br>US Census Bureau [<a href=" https://www.census.gov/data.html">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/3366423.3380021">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3485447.3512026">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3465058">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/9458599/9458600/09458698.pdf">Paper</a>][<a href="https://www.mdpi.com/2071-1050/14/19/12397/pdf">Paper</a>]<br>[<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09973276.pdf">Paper</a>]</td>
</tr>
<tr>
    <td>Logistics</td>
    <td>Spatio-temporal Trajectory</td>
    <td>LaDe [<a href="https://cainiaotechai.github.io/LaDe-website/">Link</a>]<br>JD Logistics [<a href=" https://corporate.jd.com/ourBusiness\#jdLogistics">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://arxiv.org/pdf/2306.10675">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3534678.3539027">Paper</a>]</td>
</tr>

<tr>
    <td rowspan="3">Social Network Data</td>
    <td>Text</td>
    <td>Text</td>
    <td>Twitter [<a href="https://developer.twitter.com/en/docs">Link</a>]<br>Common Crawl [<a href="https://registry.opendata.aws/commoncrawl/">Link</a>]<br>Yelp Reviews [<a href="https://www.yelp.com/dataset">Link</a>]<br>Weibo Traffic Police [<a href="http://open.weibo.com/developers/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="http://dx.doi.org/10.1109/TKDE.2022.3218851">Paper</a>][<a href="http://dx.doi.org/10.1145/2983323.2983850">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.14778/3007263.3007305">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3018661.3018680">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/2948649.2948652">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/2736277.2741675">Paper</a>][<a href="https://link.springer.com/article/10.1007/s11277-018-5495-x">Paper</a>]<br>[<a href="https://dl.acm.org/doi/abs/10.1145/3057281">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/7517494/7517753/07517782.pdf">Paper</a>][<a href="https://link.springer.com/chapter/10.1007/978-3-319-46227-1_16">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/2820783.2820829">Paper</a>][<a href="https://link.springer.com/article/10.1007/s11704-017-6464-3">Paper</a>][<a href="http://dx.doi.org/10.1109/TKDE.2020.2983892">Paper</a>]<br>[<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09075417.pdf">Paper</a>]<br>[<a href="https://ieeexplore.ieee.org/iel7/69/4358933/09075417.pdf">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.14778/3007263.3007305">Paper</a>]<br>[<a href="https://link.springer.com/article/10.1007/s42486-022-00095-5">Paper</a>]</td>
</tr>
<tr>
    <td>Geo-tagged <br> Image & Video</td>
    <td>Image & Video</td>
    <td>YFCC100M [<a href="https://goo.su/ia2DdU">Link</a>]<br>NUS-WIDE [<a href="https://goo.su/dWPQzCD">Link</a>]<br>GeoUGV [<a href="https://qualinet.github.io/databases/video/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/3123266.3123336">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3474085.3475268">Paper</a>][<a href="http://dx.doi.org/10.1109/ICDE.2019.00034">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3474085.3475268">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3347146.3359067">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/2910017.2910617">Paper</a>]</td>
</tr>
<tr>
    <td>User' Info.</td>
    <td>Time Series</td>
    <td>Jiepang User Check-in [<a href="https://jiepang.app/">Link</a>]<br>Gowalla User Location [<a href="http://konect.cc/networks/loc-gowalla_edges/">Link</a>]<br>WeChat Mobility [<a href="https://open.weixin.qq.com/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://doi.org/10.1609/aaai.v33i01.3301906">Paper</a>]<br>[<a href="http://dx.doi.org/10.1609/aaai.v29i1.9191">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3018661.3018680">Paper</a>]<br>[<a href="http://arxiv.org/abs/2111.03465">Paper</a>]</td>
</tr>
<tr>
    <td rowspan="3">Demographic Data</td>
    <td>Crime</td>
    <td>Time series</td>
    <td>NYC Crime [<a href="https://opendata.cityofnewyork.us/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="http://fi.ee.tsinghua.edu.cn/public/publications/301ad6d8-92b8-11eb-96bc-0242ac120003.pdf">Paper</a>]</td>
</tr>
<tr>
    <td>Land Use</td>
    <td>Time series</td>
    <td>Land Use SG [<a href="https://www.ura.gov.sg/Corporate/Planning/Master-Plan">Link</a>]<br>Land Use NYC [<a href="https://goo.su/puTuG">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="http://dx.doi.org/10.1145/3580305.3599538">Paper</a>]<br>[<a href="http://dx.doi.org/10.1145/3580305.3599538">Paper</a>]</td>
</tr>
<tr>
    <td>Population</td>
    <td>Time series</td>
    <td>WorldPop [<a href="https://www.worldpop.org/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="http://dx.doi.org/10.1145/3485447.3512149">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/3511808.3557153">Paper</a>][<a href="http://dx.doi.org/10.1016/j.isprsjprs.2023.05.006">Paper</a>]</td>
</tr>  
<tr>
    <td rowspan="3">Environmental Data</td>
    <td>Meteorology</td>
    <td>Time series</td>
    <td>TipDM China Weather [<a href="https://www.tipdm.org/">Link</a>]<br>DarkSky Weather [<a href="https://support.apple.com/en-us/102594">Link</a>]<br>WeatherNYC [<a href="https://opendata.cityofnewyork.us/">Link</a>]<br>WeatherChicago [<a href="https://data.cityofchicago.org/">Link</a>]<br>Weather Underground [<a href="https://www.wunderground.com/">Link</a>]<br>DidiSY [<a href="https://www.didiglobal.com/">Link</a>]<br>WD_BJ weather [<a href="https://goo.su/DmHFd">Link</a>]<br>WD_USA weather [<a href="https://goo.su/RVhBA">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://doi.org/10.1016/j.ins.2022.07.118">Paper</a>]<br>[<a href="http://dx.doi.org/10.1109/ICDE51399.2021.00037">Paper</a>]<br>[<a href="http://dx.doi.org/10.1609/aaai.v35i5.16566">Paper</a>]<br>[<a href="http://dx.doi.org/10.1609/aaai.v35i5.16566">Paper</a>]<br>[<a href="http://dx.doi.org/10.1007/s42486-022-00095-5">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3357384.3358097">Paper</a>]<br>[<a href="http://arxiv.org/abs/2201.09101">Paper</a>]<br>[<a href="http://arxiv.org/abs/2201.09101">Paper</a>]</td>
</tr>
<tr>
    <td>Greenery</td>
    <td>Time series</td>
    <td>Google Earth [<a href="https://earth.google.com/">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="http://dx.doi.org/10.1007/s42486-022-00095-5">Paper</a>]</td>
</tr>
<tr>
    <td>Air Quality</td>
    <td>Time series</td>
    <td>UrbanAir [<a href="https://goo.su/hf2NB53">Link</a>]<br>KnowAir [<a href="https://github.com/shuowang-ai/PM2.5-GNN">Link</a>]</td>
    <td style="font-size: 10px;">[<a href="https://dl.acm.org/doi/pdf/10.1145/2783258.2788573">Paper</a>][<a href="https://dl.acm.org/doi/pdf/10.1145/2487575.2488188">Paper</a>][<a href="https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/UAir20Demo.pdf">Paper</a>]<br>[<a href="https://dl.acm.org/doi/pdf/10.1145/3397536.3422208">Paper</a>][<a href="https://www.sciencedirect.com/science/article/pii/S1568494621008103/pdfft?md5=6ffecc4f1d52b9844e204d8889b96a87&pid=1-s2.0-S1568494621008103-main.pdf">Paper</a>][<a href="https://ieeexplore.ieee.org/iel7/6287639/6514899/09780279.pdf">Paper</a>][<a href="https://www.cell.com/heliyon/pdf/S2405-8440(23)04954-X.pdf">Paper</a>]</td>
</tr>


</table>

## Highly Related Paper List

The list provided below represents only a portion of the projects that we have undertaken in this field. It is important to note that this list is **not exhaustive** and will be **continuously updated**.

*Please find below a partial list of our laboratory's highly relevant projects in multimodal data fusion in urban computing:*


### [Future Intelligence Lab (FIB) (THU)](https://fi.ee.tsinghua.edu.cn/)
 

  - Will You Come Back / Check-in Again? Understanding Characteristics Leading to Urban Revisitation and Re-check-in
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3411812?casa_token=-603bVK6scwAAAAA:13Whn8f41erDnU4x9ttxXyCUQfGjJzMik8jn2Sf9kt0IYUXrT9x7-c_evhMfc37VLhxL6aezYCfl95Ig)] <br>  *In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 2020*
  - Spatio-Temporal Vehicle Trajectory Recovery on Road Network Based on Traffic Camera Video Data 
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539186)] <br>*In Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining, 2022*
  - Beyond the First Law of Geography: Learning Representations ofSatellite Imagery by Leveraging Point-of-Interests
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3485447.3512149)] <br>*In ACM Web Conference, 2022*
  - Spatio-Temporal Urban Knowledge Graph Enabled Mobility Prediction 
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3494993)]<br>*In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 2021*
  - Vehicle Trajectory Recovery on Road Network Based on Traffic Camera Video Data
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3474717.3483987?casa_token=r4GTEmlgSw0AAAAA:xf6jN-fH70AW65lWF7JL82CvYxYshvS1b9-rQe9Sww8UI0j5nrI9ScjB2euIdP9Zt_2FRpczvpoi6lVC)]<br>*In Proceedings of the 29th International Conference on Advances in Geographic Information Systems, 2021.*
  - Predicting multi-level socioeconomic indicators from structural urban imagery 
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3511808.3557153)]<br>*In Proceedings of the 31st ACM International Conference on Information & Knowledge Management, 2022*
  - Knowledge-infused Contrastive Learning for Urban Imagery-based Socioeconomic Prediction
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3543507.3583876)]<br>*In ACM Web Conference, 2023*
  - Multi-View Joint Graph Representation Learning for Urban Region Embedding
  [[paper](https://fi.ee.tsinghua.edu.cn/public/publications/301ad6d8-92b8-11eb-96bc-0242ac120003.pdf)]<br>*In Proceedings of the Twenty-Ninth International Conference on International Joint Conferences on Artificial Intelligence, 2021*
  - DeepSTN+: Context-Aware Spatial-Temporal Neural Network for Crowd Flow Prediction in Metropolis
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/3892)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2019*

### [Database Research Group (THU)](https://dbgroup.cs.tsinghua.edu.cn/ligl/index.html)
  - An Effective Joint Prediction Model for Travel Demands and Traffic Flows.
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9458698&casa_token=MaWtkqMEWUUAAAAA:fzmHqfiVsKMVPPYfRV1f9wdyr1jKdVpLlPIphl7Z6ioXE0tvFv_-CIjif62LnBrCZpaDwuBwhIjIeM8&tag=1)]<br> *In Proceedings of the IEEE 37th International Conference on Data Engineering, 2021*

### [BIGSCity Lab (BUAA)](https://www.bigscity.com/jingyuan-wang/)
  - A force-directed approach to seeking route recommendation in ride-on-demand service using multi-source urban data
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9238459&casa_token=KDIHSyCbjKgAAAAA:HqI7iwTEB5YqDECOkfZ1DidS2sx2iq6uM48TXRlzX3WyL8QqyWf2z0tAhtFkDEfLoWXln-OEwJ6Q4C8&tag=1)]<br>*In IEEE Transactions on Mobile Computing, 2020*
  - Rod-revenue: Seeking strategies analysis and revenue prediction in ride-on-demand service using multi-source urban data
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8733999&casa_token=lhJGs3710j8AAAAA:VhS8TO4oyI1uU-Fe-TNbogjxVoHmXHAAJX15ciwL0w5nHIMlcJl-WbsQAJpgD2soweuEpA5l_OUROSc)]<br>*In IEEE Transactions on Mobile Computing, 2019*

### [BJTU Lab](https://faculty.bjtu.edu.cn/8793/)
  - GSNet: Learning Spatial-Temporal Correlations from Geographical and Semantic Aspects for Traffic Accident Risk Forecasting
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/16566)] <br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2021*
  - Modeling Spatial--Temporal Constraints and Spatial-Transfer Patterns for Couriers’ Package Pick-up Route Prediction
  [[paper](https://ieeexplore.ieee.org/abstract/document/10225450?casa_token=0OpDHNDXZXUAAAAA:XOQ7qQ8943luPxzI2cOCJGgeY5Jr2tUkwmWgTMOJ_l8WpWj3bVYvWyhcUP7hRWnuw3vhSwFHqg_tPw)] <br>*In IEEE Transactions on Intelligent Transportation Systems, 2023*

### [BUCT Lab](https://www.researchgate.net/lab/Danhuai-Guo-Lab)
  - Inferring region significance by using multi-source spatial data 
  [[paper](https://link.springer.com/article/10.1007/s00521-019-04070-7)]<br>*In Neural Computing and Applications, 2020*

### [SDU Lab](https://faculty.sdu.edu.cn/chenmeng2/en/index/815589/list/index.htm)
  - Pre-Trained Semantic Embeddings for POI Categories Based on Multiple Contexts
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9935324&casa_token=Qu2MdD7JA5QAAAAA:k8kbEUxYfPRyTIzUb29rPEzyA61DwUZ5PzJlwFiruEYAxm1KoEhIZzPly1AJztKV18wdw_arlvkjHis&tag=1)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2022*

### [UESTC Lab](https://zheng-kai.com/)
  - Photo2Trip: Exploiting Visual Contents in Geo-tagged Photos for Personalized Tour Recommendation
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3123266.3123336?casa_token=3oivUX5VwrYAAAAA:-2Qoyg8f5yZRjcH3ebZL-z6dDYZxOKRNLGLrIfkdxVJ4-qa-tHUtIsY0c1MIdlUTQL39Uj2_pywN0c2e)]<br>*In Proceedings of the 25th ACM International Conference on Multimedia, 2017*

### [CPS-DSC Lab(CQU)](http://cps.cqu.edu.cn/info/1006/1647.htm)
  - TripPlanner: Personalized Trip Planning Leveraging Heterogeneous Crowdsourced Digital Footprints
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=6951432&casa_token=RHnlU4MWS-AAAAAA:LQ9gSNTx_KByl4JRJeHbhRZKbbZF4vSeQNESLSX6TS8ErIe4qL7DhoEbD249JdzLG46vUmipzKbv7EU)]<br>*In IEEE Transactions on Intelligent Transportation Systems, 2014*

### [Cloud Computing and Intelligent Techniques Lab (SWJTU)](https://faculty.swjtu.edu.cn/litianrui/en/index/33185/list/index.htm)
  - Forecasting Fine-Grained Air Quality Based on Big Data
  [[paper](https://dl.acm.org/doi/pdf/10.1145/2783258.2788573?casa_token=DepF7HHb9E8AAAAA:Me3v68Ijh5ohYgXyn3P4BJZBbBF8IHCmBFWDr1TmDnhiSkHjyuWP0HuAzplzAtkqrxXtlcN1fv9GSLgK)]<br>*In Proceedings of the 21st ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2015*
  - Urban Sensing Based on Human Mobility
  [[paper](https://dl.acm.org/doi/pdf/10.1145/2971648.2971735?casa_token=x-A0VT2gRjsAAAAA:haY3mv9ZnLSOOXptCRk-FJy2JRFVIf88Z2of122Vld9_fiQMBVLSL5DQdOl05eU-298B_WouherkjRHd)]<br>*In Proceedings of the 2016 ACM International Joint Conference on Pervasive and Ubiquitous Computing, 2016*
  - Dual-grained human mobility learning for location-aware trip recommendation with spatial–temporal graph knowledge fusion
  [[paper](https://dl.acm.org/doi/pdf/10.1145/2971648.2971735?casa_token=x-A0VT2gRjsAAAAA:haY3mv9ZnLSOOXptCRk-FJy2JRFVIf88Z2of122Vld9_fiQMBVLSL5DQdOl05eU-298B_WouherkjRHd)]<br>*In Information Fusion, 2023*
  - Symbolic aggregate approximation based data fusion model for dangerous driving behavior detection
  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025522008076)]<br>*In Information Sciences, 2022*
  - Contextual spatio-temporal graph representation learning for reinforced human mobility mining
  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025522004819)]<br>*In Information Sciences, 2022*
  - HiSTGNN: Hierarchical spatio-temporal graph neural network for weather forecasting   [[paper](https://zhangjunbo.org/pdf/2023_INS_HiSTGNN.pdf)]<br>*In Information Sciences, 2023*
  - Modeling multi-regional temporal correlation with gated recurrent unit and multiple linear regression for urban traffic flow prediction  [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705122013338)]<br>*In Knowledge-Based Systems, 2023*
  - Predicting citywide crowd flows using deep spatio-temporal residual networks   [[paper](https://www.sciencedirect.com/science/article/pii/S0004370218300973)]<br>*In Elsevier, 2018*

### [SUSTech Lab](https://www.sustech.edu.cn/en/faculties/songxuan.html)
  - DeepTransport: Prediction and Simulation of Human Mobility and Transportation Mode at a Citywide Level
  [[paper](https://dl.acm.org/doi/abs/10.5555/3060832.3060987)]<br>*In Proceedings of the Twenty-Fifth International Joint Conference on Artificial Intelligence, 2016*
  - Optimization of Causative Factors for Landslide Susceptibility Evaluation Using Remote Sensing and GIS Data in Parts of Niigata, Japan
  [[paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0133262)]<br>*In PloS One, 2015*
  - DeepMob: Learning Deep Knowledge of Human Emergency Behavior and Mobility from Big and Heterogeneous Data
  [[paper](https://dl.acm.org/doi/abs/10.1145/3057280?casa_token=RDXjxqCYCCEAAAAA:iXOtzNRcK_fO5bKzVA9GgKtIoQRho1cJSerow7khjv7Jh0c_VD5wULGeUC_EkAINn0vdvL2VuZkJ_I2h)]<br>*In ACM Transactions on Information Systems, 2017*
  - DeepUrbanEvent: A System for Predicting Citywide Crowd Dynamics at Big Events
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3292500.3330654?casa_token=1-tOoL9o8jIAAAAA:_vaxaOlhK7v-Ry480JpcKkBhhJhtkhylJ1M2cVGJwulqPYixYadUo7ZrihS3CfDFQunNfFW7hmRuZF3e)]<br>*In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, 2019*
  - DeepMob: Integrating GPS trajectory and topics from Twitter stream for human mobility estimation
  [[paper](https://journal.hep.com.cn/fcs/EN/article/downloadArticleFile.do?attachType=PDF&id=19960)]<br>*In Frontiers of Computer Science, 2019*

### [Big Data for Urban Intelligence Lab (CSU)](https://faculty.csu.edu.cn/wangsenzhang/en/index.htm) 
  - Citywide traffic congestion estimation with social media
  [[paper](https://dl.acm.org/doi/abs/10.1145/2820783.2820829)]<br>*In Proceedings of the 23rd SIGSPATIAL International Conference on Advances in Geographic Information Systems, 2015*
  - Estimating Urban Traffic Congestions with Multi-sourced Data
  [[paper](https://ieeexplore.ieee.org/abstract/document/7517782?casa_token=H4WsNdho-kgAAAAA:W6-cfFsKIaaZaFl2ZTMmQHwF_nIGlf8w6CLCmq2LPXCDWD8d1NucR_hFmKrYqbYWbgZTya22KmMXyxU)]<br>*In Proceedings of the 17th IEEE International Conference on Mobile Data Management, 2016*
  - Enhancing Traffic Congestion Estimation with Social Media by Coupled Hidden Markov Model
  [[paper](https://link.springer.com/chapter/10.1007/978-3-319-46227-1_16)]<br>*In Proceedings of the European Conference on Machine Learning and Knowledge Discovery in Databases (ECML PKDD), 2016*
  - Computing urban traffic congestions by incorporating sparse GPS probe data and social media data
  [[paper](https://dl.acm.org/doi/abs/10.1145/3057281)]<br>*In ACM Transactions on Information Systems, 2017*
  - Forecasting Citywide Traffic Congestion Based on Social Media
  [[paper](https://link.springer.com/article/10.1007/s11277-018-5495-x)]<br>*In Wireless Personal Communications, 2018*
  - Traffic Accident Risk Prediction via Multi-View Multi-Task Spatio-Temporal Networks
  [[paper](https://ieeexplore.ieee.org/abstract/document/9652050?casa_token=W0joK3Xd_7AAAAAA:rGqepn974PlPEVxopN65ua-AVxuKp5GYXjRZC3prlD0cdnYpRBa9yaOwZ4zrHRSJX7xNPX5rLiuSRD8)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2021*


### [CityMind Lab (USTGZ)](https://yuxuanliang.com/)
  - When Urban Region Profiling Meets Large Language Models
  [[paper](https://arxiv.org/abs/2310.18340)]<br>*In Proceedings of the Web Conference, 2024*
  - Airformer: Predicting nationwide air quality in china with
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/26676)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2023*
  - Beyond Geo-localization: Fine-grained Orientation of Street-view Images by Cross-view Matching with Satellite Imagery
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3503161.3548102)]<br>*In Proceedings of the 30th ACM International Conference on Multimedia, 2022*
  - Learning Multi-context Aware Location Representations from Large-scale Geotagged Images
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3474085.3475268)]<br>*In Proceedings of the 29th ACM International Conference on Multimedia, 2021*
  - Fine-Grained Urban Flow Prediction
  [[paper](https://dl.acm.org/doi/abs/10.1145/3442381.3449792)]<br>*In Proceedings of the Web Conference, 2021*
  - Geoman: Multi-level attention networks for geo-sensory time series prediction
  [[paper](https://www.researchgate.net/profile/Yuxuan-Liang-2/publication/326205629_GeoMAN_Multi-level_Attention_Networks_for_Geo-sensory_Time_Series_Prediction/links/5bea6e4b92851c6b27ba5164/GeoMAN-Multi-level-Attention-Networks-for-Geo-sensory-Time-Series-Prediction.pdf)]<br>*In Proceedings of the Web Conference, 2021*
  - Fine-Grained Urban Flow Prediction
  [[paper](https://dl.acm.org/doi/abs/10.1145/3442381.3449792)]<br>*In Proceedings of the Web Conference, 2021*
  - Urbanfm: Inferring fine-grained urban flows
  [[paper](https://dl.acm.org/doi/abs/10.1145/3292500.3330646?casa_token=D3fnWUWi7oEAAAAA:_POC1ziZe29XyRV3oQ2UZ9S_udCjfjbPH26dQYkPieGO2TLjGFS2Ig8MVzFll-2L534h-p6-x685Uko)]<br>*In Proceedings of the 25th ACM SIGKDD international conference on knowledge discovery, 2019*
  - Diffstg: Probabilistic spatio-temporal graph forecasting with denoising diffusion models
  [[paper](https://dl.acm.org/doi/abs/10.1145/3589132.3625614?casa_token=Qgk8A-QEelkAAAAA:wrUje41Kz40-nrf-w1c9ddFRilZno1pd2AW5HvtDfxU39GBc-4PULSTYdC0No6wDPVSNVYf14ABC8xg)]<br>*In Proceedings of the Joint Conference on Artificial Intelligence, 2023*


### [Data Intelligence Lab (HKU)](https://sites.google.com/view/chaoh)
  - Spatio-Temporal Meta Contrastive Learning
  [[paper]([https://dl.acm.org/doi/abs/10.1145/3583780.3615065?casa_token=ceZsuOvI4kEAAAAA:6t1ZbycWqtmhtnBrvYNKae9cef6wJ3Taa82u3eXLJKvgACdd7PINdk_vrxwv35GLVFlStRJ9rn-5F-E))]<br>*Proceedings of the ACM International Conference on Information and Knowledge Management, 2023*
  - Exploiting spatial-temporal-social constraints for localness inference using online social media
  [[paper](https://ieeexplore.ieee.org/abstract/document/7752247)]<br>*In Proceedings of the IEEE/ACM International Conference on Advances in Social Networks Analysis and Mining (ASONAM), 2016*
  - DeepCrime: Attentive hierarchical recurrent networks for crime prediction
  [[paper]([https://dl.acm.org/doi/abs/10.1145/3269206.3271793))]<br>*Proceedings of the ACM international conference on information and knowledge management, 2018*

### [ASC Lab (XMU)](https://fanxlxmu.github.io/)
  - PANDA: predicting road risks after natural disasters leveraging heterogeneous urban data
  [[paper](https://link.springer.com/article/10.1007/s42486-022-00095-5)]<br>*In CCF Transactions on Pervasive Computing and Interaction, 2022*
  - UVLens: Urban Village Boundary Identification and Population Estimation Leveraging Open Government Data
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3463495)]<br>*In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 2021*
  - iTV: Inferring Traffic Violation-Prone Locations With Vehicle Trajectories and Road Environment Data
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9171429)]<br>*In IEEE Systems Journal, 2021*
  - RADAR: Road Obstacle Identification for Disaster Response Leveraging Cross-Domain Urban Data
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3161159)]<br>*In Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, 2018*

### [KDD Lab (UCF)](https://yanjiefu.com/)
  - Unified route representation learning for multi-modal transportation recommendation with spatiotemporal pre-training
  [[paper]([https://link.springer.com/article/10.1007/s42486-022-00095-5](https://link.springer.com/article/10.1007/s00778-022-00748-y))]<br>*In The VLDB Journal, 2023*
  - NodeSense2Vec: Spatiotemporal Context-Aware Network Embedding for Heterogeneous Urban Mobility Data
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9672072)]<br>*In Proceedings of the IEEE International Conference on Big Data (Big Data), 2021*
  - Collective embedding with feature importance: A unified approach for spatiotemporal network embedding
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3340531.3412030)]<br>*In Proceedings of the 29th ACM International Conference on Information & Knowledge Management, 2020*
  - Beyond Geo-First Law: Learning Spatial Representations via Integrated Autocorrelations and Complementarity
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8970913)]<br>*In Proceedings of the IEEE International Conference on Data Mining (ICDM), 2019*
  - Joint Representation Learning for Multi-Modal Transportation Recommendation
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/download/3894/3772)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2019*
  - Efficient Region Embedding with Multi-View Spatial Networks:A Perspective of Locality-Constrained Spatial Autocorrelations
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/3879/3757)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2019*
  - Human-instructed deep hierarchical generative learning for automated urban planning
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/25589)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2023*
  - Deep human-guided conditional variational generative modeling for automated urban planning
  [[paper](https://ieeexplore.ieee.org/abstract/document/9679173?casa_token=2L4pfiDrLU8AAAAA:b1Sbz5Elarg303r1ycYGyH2tatlZU3HI30GEA53UyzLNRjNDoyW8ZPwfhZZ8wWocAxoMlIH7Jvd9Lw)]<br>*In IEEE international conference on data mining, 2021*


### [Gatech Lab](http://chaozhang.org/)
  - Spatiotemporal Activity Modeling via Hierarchical Cross-Modal Embedding
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9050875)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2020*

### [Big Data and Database Group (RMIT)](https://baozhifeng.net/)
  - Similar Trajectory Search with Spatio-Temporal Deep Representation Learning
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3466687)]<br>*In ACM Transactions on Intelligent Systems and Technology, 2021*
  - An Effective Joint Prediction Model for Travel Demands and Traffic Flows
  [[paper](https://ieeexplore.ieee.org/iel7/9458599/9458600/09458698.pdf)]<br>*In Proceedings of the IEEE 37th International Conference on Data Engineering (ICDE), 2021

### [Artificial Intelligence (AI) research group (UniMelb)](https://people.eng.unimelb.edu.au/jianzhongq/)
  - A Joint Context-Aware Embedding for Trip Recommendations
  [[paper](https://ieeexplore.ieee.org/iel7/8725877/8731337/08731399.pdf)]<br>*In Proceedings of the IEEE 35th International Conference on Data Engineering (ICDE), 2019*

### [Context Recognition and Urban Intelligence (CRUISE) Lab (UNSW)](https://cruiseresearchgroup.florasalim.com/)
  - Multimodal Trajectory Prediction: A Survey
  [[paper](https://arxiv.org/pdf/2302.10463)]<br>*In arXiv, 2023*
  - Explainable spatiotemporal reasoning for geospatial intelligence applications
  [[paper](https://onlinelibrary.wiley.com/doi/pdf/10.1111/tgis.12939)]<br>*In Transactions in GIS, 2022*
  - Event-Aware Multimodal Mobility Nowcasting
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/download/20342/20101)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2022*
  - Beyond Just Vision: A Review on Self-Supervised Representation Learning on Multimodal and Temporal Data
  [[paper](https://arxiv.org/pdf/2206.02353)]<br>*In arXiv, 2022*

### [Baidu Intelligent Driving Group (IDG) (Baidu Map)](https://huangjizhou.github.io/)
  - DuARE: Automatic Road Extraction with Aerial Images and Trajectory Data at Baidu Maps
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539029)]<br>*In Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining, 2022*
  - ERNIE-GeoL: A Geography-and-Language Pre-trained Model and its Applications in Baidu Maps
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3534678.3539021)]<br>*In Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining, 2022*
  - DuTraffic: Live Traffic Condition Prediction with Trajectory Data and Street Views at Baidu Mapss
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3511808.3557151)]<br>*In Proceedings of the 31st ACM International Conference on Information & Knowledge Management, 2022*
  - A Contextual Master-Slave Framework on Urban Region Graph for Urban Village Detection
  [[paper](https://ieeexplore.ieee.org/iel7/10184508/10184509/10184898.pdf)]<br>*In Proceedings of the IEEE 39th International Conference on Data Engineering (ICDE), 2023*

### [Shanghai AI Lab](http://leibai.site/)
  - Jointly Contrastive Representation Learning on Road Network and Trajectory
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3511808.3557370)]<br>*In Proceedings of the 31st ACM International Conference on Information & Knowledge Management, 2022*
  - Spatio-Temporal Graph Convolutional and Recurrent Networks for Citywide Passenger Demand Prediction
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3511808.3557370)]<br>*In Proceedings of the 28th ACM International Conference on Information and Knowledge Management, 2019*
  - STG2Seq: Spatial-temporal Graph to Sequence Model for Multi-step Passenger Demand Forecasting
  [[paper](https://arxiv.org/pdf/1905.10069)]<br>*In arXiv, 2019*

### [Alibaba Group](http://www.yelabs.net/)
  - Joint predictions of multi-modal ride-hailing demands: A deep multi-task multi-graph learning-based approach
  [[paper](https://arxiv.org/pdf/2011.05602)]<br>*In Transportation Research Part C: Emerging Technologies, 2021*
  - Multi-modal graph interaction for multi-graph convolution network in urban spatiotemporal forecasting
  [[paper](https://www.mdpi.com/2071-1050/14/19/12397/pdf)]<br>*In Sustainability, 2022*

### [PSU Group](https://faculty.ist.psu.edu/jessieli/Site/index.html)
  - Unsupervised Representation Learning of Spatial Data via Multimodal Embedding
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3357384.3358001)]<br>*In Proceedings of the 28th ACM International Conference on Information and Knowledge Management, 2019*
  - Deep multi-view spatial-temporal network for taxi demand prediction
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/11836/11695)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2018*

### [JD Intelligent Cities Research Lab](http://urban-computing.com/yuzheng)
  - Forecasting fine-grained urban flows via spatio-temporal contrastive self-supervision
  [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9864246)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2022*
  - Spatio-Temporal Self-Supervised Learning for Traffc Flow Prediction
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/download/25555/25327)]<br>*In Proceedings of the AAAI Conference on Artificial Intelligence, 2023*
  - Spatio-Temporal Contrastive Self-Supervised Learning for POI-level Crowd Flow Inference
  [[paper](https://arxiv.org/pdf/2309.03239)]<br>*In arXiv, 2023*
  - A Cross-City Federated Transfer Learning Framework: A Case Study on Urban Region Profiling
  [[paper](https://arxiv.org/pdf/2206.00007)]<br>*In arXiv, 2022*
  - Predicting citywide crowd flows in irregular regions using multi-view graph convolutional networks
  [[paper](https://ieeexplore.ieee.org/abstract/document/9139357?casa_token=18aTwLyqQFgAAAAA:8kpYoCo98F6F02eKgNd13pAZARF-o6Zi1xLLKHKOZTNzliOaLG5om8vwFKhjSDAXPAQ0WXAiV3NSTg)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2020*
  - Urban computing: concepts, methodologies, and applications
  [[paper](https://dl.acm.org/doi/abs/10.1145/2629592?casa_token=GJg1l-w0qpEAAAAA:MVmdP_UiUb8wYJZpxNQYmx37K2ethon2GEz6zhctCdXjRwzIRKrDEiz6pLhJs1ib34Vls5l8XsDPIWE)]<br>*In ACM Transactions on Intelligent Systems and Technology, 2014*
  - Traffic flow forecasting with spatial-temporal graph diffusion network
  [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/17761)]<br>*In Proceedings of the AAAI conference on artificial intelligence, 2021*
  - Spatio-temporal meta learning for urban traffic prediction
  [[paper](https://ieeexplore.ieee.org/abstract/document/9096591?casa_token=owlhI1Np87IAAAAA:owJ5pUMkYJUO5KLCtUs8bFuGcUVfM70kLMQSf6P_yvj_hRhiKZXDJNsYwLT7m4kj6cICIaGkRJ1r6g)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2020*
  - Deep distributed fusion network for air quality prediction
  [[paper](https://dl.acm.org/doi/abs/10.1145/3219819.3219822?casa_token=uUJKpgya6ZUAAAAA:9V77Z0v8okng5JwoZt-xlQGxpx2b-b2FVD7f2-abbVVixaXUze-jo_dVkEREPuOtZZc50G6X7JTTMTI)]<br>*In Proceedings of the 24th ACM SIGKDD international conference on knowledge discovery \& data mining, 2018*
  - Service Time Prediction for Delivery Tasks via Spatial Meta-Learning
  [[paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539027?casa_token=qxAs8hXH36EAAAAA:7GYvl46x1p5HJ_CqmMjOILj80-3rtMALhGbl6wlaq_qXaLMiX-VxzsB_0hin6hSNu73pBj7kCFFdTDw)]<br>*In Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining, 2022*
  - Spatio-Temporal Graph Neural Networks for Predictive Learning in Urban Computing: A Survey
  [[paper](https://ieeexplore.ieee.org/abstract/document/10328393?casa_token=czrIZYU3lHsAAAAA:aTyCK-BAUo6CxZEEM-GWlPU_unnggwYkMCgvH53MgE0ODEbOt0HYv4R6b-lZUCf21Wgt5SCvFBpZtg)]<br>*In IEEE Transactions on Knowledge and Data Engineering, 2023*
  - SAInf: Stay Area Inference of Vehicles using Surveillance Camera Records
  [[paper](http://urban-computing.com/pdf/KDD2023_stay.pdf)]<br>*In urban-computing.com, 2023*












