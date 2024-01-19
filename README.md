<p align="center">

  <h1 align="center">Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences</h1>
  <p align="center">
    <a><strong>Xiyao Wang</strong></a>
    ·
    <a><strong>Yuhang Zhou</strong></a>
    ·
    <a><strong>Xiaoyu Liu</strong></a>
    ·
    <a><strong>Hongjin Lu</strong></a>
    ·
    <a><strong>Yuancheng Xu</strong></a>
    ·
    <a><strong>Feihong He</strong></a>
    ·
    <a><strong>Jaehong Yoon</strong></a>
    ·
    <a><strong>Taixi Lu</strong></a>
    ·
    <a><strong>Gedas Bertasius</strong></a>
    ·
    <a><strong>Mohit Bansal</strong></a>
    ·
    <a><strong>Huaxiu Yao*</strong></a>
    ·
    <a><strong>Furong Huang*</strong></a>
  </p>

</p>

# Dataset
This is the dataset and code for paper 'Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences'

All datas are at this google drive link: [Menmentos Dataset](https://drive.google.com/drive/folders/1CKBWtHKzJgkGJb3Qdl2e_HHhc0fThW61?usp=sharing)

# Synonym graphs
We provide all object and behavior synonym files in 'sym_graphs' folder which can be loaded and used directly using function 'load_graph' in [build_action_graph.ipynb](https://github.com/si0wang/Mementos/blob/main/sym_graphs/build_action_graph.ipynb).

# Evaluation
To evaluate your own model, we provide the codes of GPT-4-assisted evaluation procedure in [GPT-4-assisted_evaluation.ipynb](https://github.com/si0wang/Mementos/blob/main/GPT-4-assisted_evaluation.ipynb).
First you need extract object and behavior keyword list using GPT-4, then compute Recall, Precision, and F1 of objects and behaviors.
