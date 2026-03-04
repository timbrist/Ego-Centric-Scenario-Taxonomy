# Ego-Centric-Scenario-Taxonomy

This repository contains resources for the paper "Evaluating LLM Driving Explanations through an Ego-Centric
Scenario Taxonomy" by Shengheng Yan and Tsvetomila Mihaylova, published as a late-breaking report at [HRI 2026](https://humanrobotinteraction.org/2026/).

The following resources are available:

* Ego-centric taxonomy of driving situations, grounded in existing scenario taxonomies but tailored for explanation evaluation.

* Annotations with the low-level taxonomy categories of the BDD-X test set.

* Code for evaluation on two methods -- zero-shot results for GPT-4o and results from a trained [RAG-Driver](https://github.com/YuanJianhao508/RAG-Driver).


## Taxonomy

The folder `taxonomy` contains `csv` and `json` files with the proposed ego-centered taxonomy.

## Annotations

The folder `annotations` contains the annotations with the low-level categories of the proposed ego-centric taxonomy of the [BDD-X test set](https://raw.githubusercontent.com/YuanJianhao508/RAG-Driver/refs/heads/main/evalcap/BDDX_gt/conversation_bddx_eval.json), as split by RAG-Driver.

The file `bddx_test_with_justification_category.csv` contains the BDD-X test set annoatated with the low-level categories from the taxonomy. Some situations have more than one category.


## Code

### Training Code

### Evaluation Code

### Classification of Driving Categories


## Citation

If you find our work helpful, please cite it as follows:

```
@inproceedings{yan2026evaluating,
  author    = {Shengheng Yan and Tsvetomila Mihaylova},
  title     = {Evaluating LLM Driving Explanations through an Ego-Centric Scenario Taxonomy},
  booktitle = {Companion Proceedings of the 21st ACM/IEEE International Conference on Human-Robot Interaction (HRI Companion '26)},
  year      = {2026},
  address   = {Edinburgh, Scotland, UK},
  publisher = {ACM},
  doi       = {10.1145/3776734.3794466},
  isbn      = {979-8-4007-2321-6}
}
```