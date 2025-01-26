# Idea Visual
This is an anonymous code and dataset release for SIGGRAPH 2025 submission "Idea Visual: Intent-Driven View Synthesis via Multimodal Diffusion Model".

## TODO
- [x] Benchmark.
- [x] Models and tools.
- [ ] Training code and inference code.
- [ ] Checkpoints.

❗️To resist plagiarism, Training code and Inference code will be available upon acceptance.

## Preparation

To start, we prefer creating the environment using conda:

```
conda env create -f environment.yml
conda activate IdeaVisual
```

Alternatively use

```
pip install -r requirements.txt
```

## Getting the data

- Download benchmark [Answerer](https://1drv.ms/u/s!AoXcO8rD9StlbTeugyChsRUkzQM?e=i9QaKy).

- We have updated the `tools` folder, which contains multiple Python scripts for operating [Objaverse](https://objaverse.allenai.org/). With these scripts, users can create `Answerer` target categories according to their expectations. Additionally, the `tools/dataAPI.py` includes the `system prompt` used when constructing the Answerer, and you can use this prompt to independently verify the descriptive effectiveness of the views.

## Models
