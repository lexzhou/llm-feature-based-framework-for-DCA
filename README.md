# An LLM Feature-based Franework for Dialogue Constructiveness Assessment
This repository bundles the code associated with the paper: [An LLM Feature-based Franework for Dialogue Constructiveness Assessment](https://arxiv.org/pdf/2406.14760).

## Structure
The codebase is a mix of three modules:

```bash
# Raw data of the three datasets of our analysis: OUM, Wikitactics and AFD. These are needed to run the scripts in "experiments" and "feature_engineering" folders.
rawdata/

# Scripts for the training and evaluation of the LLM feature-based models and the baselines.
experiments/

# Scripts for generating the discrete and LLM-generated features in tandem with the resultant labeled datasets, which are needed to run the scripts in "experiments" module.
feature_engineering/
```

## Citation
Please cite our paper if you use our framework, codebase, or part of it in your work:

```bibtex
@article{zhou2024llm,
  title={An LLM Feature-based Framework for Dialogue Constructiveness Assessment},
  author={Zhou, Lexin and Farag, Youmna and Vlachos, Andreas},
  journal={arXiv preprint arXiv:2406.14760},
  year={2024}
}
```