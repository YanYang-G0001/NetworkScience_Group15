Readme
# Analysis of Software Dependency Networks: A Comparison of Python, R, and Java Ecosystems

This repository is part of a robustness analysis of package dependency networks. It includes the raw dataset, preprocessed data, and code for preprocessing and calculating various metrics. To facilitate code reuse and enable quick review of our results at each step, we have organized the work into separate Jupyter notebooks, with each notebook covering a distinct part of the analysis.

## Raw Data
The [original dataset](https://github.com/YanYang-G0001/NetworkScience_Group15/tree/31e058669bdaafb4c55e6daf4d7b227262ac33c7/data_origin) can be downloaded directly from the repository. We used data from the Colorado Index of Complex Networks[1], a dataset provided by the University of Colorado that indexes real-world networks. Specifically, we analyzed Python, R, and Java dependency networks. For more information, please refer to the [website](https://icon.colorado.edu).

## Preprocessed Data
We transferred the original csv file into directed network using [data_preprocessing.ipynb](https://github.com/YanYang-G0001/NetworkScience_Group15/blob/31e058669bdaafb4c55e6daf4d7b227262ac33c7/Data_Preprocessing.ipynb). Alternatively, user can download the [preprocessed data](https://github.com/YanYang-G0001/NetworkScience_Group15/tree/31e058669bdaafb4c55e6daf4d7b227262ac33c7/data_preprocessed) directly.

## Analysis
To conduct basic analysis (degree distribution, assortativity, and community detection) and simulate random attack, please refer to [Basic_Analysis_&_Random_Attack.ipynb](https://github.com/YanYang-G0001/NetworkScience_Group15/blob/31e058669bdaafb4c55e6daf4d7b227262ac33c7/Basic_Analysis_%26_Random_Attack.ipynb).
To calculate dynamical importance, please refer to [Dynamical_Importance.ipynb](https://github.com/YanYang-G0001/NetworkScience_Group15/blob/31e058669bdaafb4c55e6daf4d7b227262ac33c7/Dynamical_Importance.ipynb).
To analyze betweenness central, please refer to [Between_Centrality.ipynb](https://github.com/YanYang-G0001/NetworkScience_Group15/blob/31e058669bdaafb4c55e6daf4d7b227262ac33c7/Between_Centrality.ipynb).
To understand the implementation and the calculation of Network
Vulnerability Index method, please refer to [Network_Vulnerability_Index.ipynb](https://github.com/YanYang-G0001/NetworkScience_Group15/blob/31e058669bdaafb4c55e6daf4d7b227262ac33c7/Network_Vulnerability_Index.ipynb).

## Contributors
Group 15
- **Qiyao Zheng** - [Github](https://github.com/qiyaozheng)
- **Yanyang Gong** - [Github](https://github.com/YanYang-G0001)
- **Yunfan Zhou** - [Github](https://github.com/saluttolove)
- **Xin Zhong**

  
## Reference
[1] Clauset, A., Tucker, E., Sainz, M.: The Colorado Index of Complex Networks. https://icon.colorado.edu (2016)

