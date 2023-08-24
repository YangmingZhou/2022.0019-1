# 2022.0019
# [Heuristic Search for Rank Aggregation with Application to Label Ranking](https://doi.org/10.1287/ijoc.2022.0019)
This archive is distributed in association with the [INFORMS Journal on Computing](https://pubsonline.informs.org/journal/ijoc) under the MIT License.

## Abstract
Rank aggregation combines the preference rankings of multiple alternatives from different voters into a single consensus ranking, providing a useful model for a variety of practical applications, but posing a computationally challenging problem. In this paper, we provide an effective hybrid evolutionary ranking algorithm to solve the rank aggregation problem with both complete and partial rankings. The algorithm features a semantic crossover based on concordant pairs and an enhanced late acceptance local search method reinforced by a relaxed acceptance and replacement strategy and a fast incremental evaluation mechanism. Experiments are conducted to assess the algorithm, indicating a highly competitive performance on both synthetic and real-world benchmark instances compared with state-of-the-art algorithms. To demonstrate its practical usefulness, the algorithm is applied to label ranking, a well-established machine learning task. We additionally analyze several key algorithmic components to gain insight into their operation.

## Keywords
Rank Aggregation; Label Ranking; Machine Learning; Evolutionary Computation; Metaheuristics.

## Instances and results
We have considered two classes of rank aggregation problem (RAP) instances, called synthetic instances and real-world instances, which can be found in the two folders "RAP_synthetic" and "RAP_realworld" of the subdirectory"data" of HER, respectively. Also, we provide benchmark datasets for label ranking (LR), called semi-synthetic datasets and real-world datasets, which can be found in the two folders "LR_synthetic" and "LR_realworld" of the subdirectory"data" of labelranking, respectively. 

The specific illustration of instances can be found in the file "readme.txt"  in each folder for each type of instance. The source files for the method HER  are in "src". The method HER is coded with C++. Guidance for implementation can be found in the file "readme.txt". Meanwhile, the results output and figures by these methods are available in the folder “results”. The data and source of label ranking are available in the folder "labelranking". Each folder also contains a "readme.txt". 

## Paper Entry
Yangming Zhou, Jin-Kao Hao, Zhen Li, Fred Glover. ["Heuristic Search for Rank Aggregation with Application to Label Ranking"](https://doi.org/10.1287/ijoc.2022.0019). INFORMS Journal On Computing, 2023.

## Cite
To cite this code, please cite the paper using its DOI and the code itself, using the following DOI.\
DOI:10.1287/ijoc.2022.0019.cd

Below is the BibTex for citing this version of the code.
~~~
@article{detectnode,
  title={Heuristic Search for Rank Aggregation with Application to Label Ranking},
  author={Yangming Zhou and Jin-Kao Hao and Zhen Li and Fred Glover},
  publisher={{INFORMS Journal on Computing}},
  year={2023},
  doi={10.1287/ijoc.2022.0019cd},
  note={available for download at https://github.com/INFORMSJoC/2022.0019}
}
~~~
