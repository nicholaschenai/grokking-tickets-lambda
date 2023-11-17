# Introduction
This work explores the role of the lottery ticket hypothesis in the process of 'grokking', and is heavily adapted from these core works:

- Progress measures for grokking via mechanistic interpretability
[[Repo](https://github.com/mechanistic-interpretability-grokking/progress-measures-paper)]
[[Paper](https://arxiv.org/abs/2301.05217)]

- Grokking Tickets: Lottery Tickets Accelerate Grokking
[[Repo](https://github.com/gouki510/Grokking-Tickets)]
[[Paper](https://arxiv.org/abs/2310.19470)]

- Quantifying degeneracy in singular models via the learning coefficient
[[Repo](https://github.com/edmundlth/scalable_learning_coefficient_with_sgld/tree/v1.0)]
[[Paper](https://arxiv.org/abs/2308.12108)]

- DevInterp library, especially their Grokking example
[[Repo](https://github.com/timaeus-research/devinterp)]
[[Notebook](https://github.com/timaeus-research/devinterp/blob/main/examples/grokking.ipynb)]

The report is available under `Lambda_Grokking_Ticket_Analysis.pdf` and the graphs are available in the `html` and `ticket_plots` folder

This mini project was done in ~16 hours as part of an interview process.

# Usage
1. Get the outputs of Nanda et. al. (2023) via the `gdown` line in `Grokking_Analysis.ipynb`

2. Use `grokking_ticket_extract.ipynb` to extract lottery tickets at various phases of grokking and train the networks

3. Use `grokking_ticket_progress_measures_graphs.ipynb` to plot metrics

4. Use `grokking_ticket_lambda_gpu.ipynb` for RLCT estimation and plotting