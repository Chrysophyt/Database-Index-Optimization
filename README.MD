# Database Index Optimization by Embedding and Deep Q-Learning
Indexing is an important task in a database. However over usage of the index writing causes severe impact on database performance especially during writing. This paper focuses on how we can avoid rebuilding index by using language model for embedding and reinforcement learning to do online index selection, which avoid the high cost of rebuilding index when new data are stored.


This repository contain a high level overview summary of "Indexer++: Workload-Aware Online Index Tuning with Transformers and Reinforcement Learning".

## Citations
```bibtex
@inproceedings{10.1145/3477314.3507691,
author = {Sharma, Vishal and Dyreson, Curtis},
title = {Indexer++: Workload-Aware Online Index Tuning with Transformers and Reinforcement Learning},
year = {2022},
isbn = {9781450387132},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3477314.3507691},
doi = {10.1145/3477314.3507691},
pages = {372–380},
numpages = {9},
keywords = {reinforcement learning, online index selection, pre-trained transformers, workload trend detection},
location = {Virtual Event},
series = {SAC '22}
}
```