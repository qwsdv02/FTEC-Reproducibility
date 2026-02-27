# FTEC5660 - Agentic AI for Finance: Reproducibility Work

This project aims to reproduce and extend the analysis of Large Language Models (LLMs) performance on the N-back working memory task.

## 🎯 Objectives
- Reproduce the original analytical pipeline for the GPT-3.5-Turbo model.
- **Key Modification**: Extend the framework to include two new models: **Qwen/Qwen3-32B** and **DeepSeek-V3.2**.
- Compare cognitive performance metrics (e.g., d-prime, accuracy) of different LLMs across varying N-back difficulty levels.

## 📂 Repository Structure
- `reproducibility_analysis.ipynb`: Main Jupyter Notebook containing data loading, processing, statistical tests, and visualizations.
- `all_trials_verbal.json`: Trial-level data from the original GPT-3.5-Turbo experiment.
- `llm_nback_results_new_experiment.csv`: Aggregated results from the new LLM experiments (Qwen, DeepSeek).

## ⚙️ Experimental Setup
- **Models Analyzed**: Qwen/Qwen3-32B, deepseek-ai/DeepSeek-V3.2, gpt-3.5-turbo
- **N-back Levels**: 1, 2, 3
- **Total Data Points**: 30 independent blocks and 720 trials
- **Development Environment**: Google Colab (Python 3.x)

## 🚀 Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/qwsdv02/FTEC-Reproducibility.git
   cd FTEC-Reproducibility
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas numpy scipy pingouin matplotlib seaborn statsmodels
   ```
3. Ensure the data files `all_trials_verbal.json` and `llm_nback_results_new_experiment.csv` are in the root directory.
4. Open and run `reproducibility_analysis.ipynb` in Jupyter Lab or Google Colab.

## 📊 Key Findings
The analysis reveals significant differences in how various LLMs respond to increasing N-back task difficulty. Detailed results, statistical outputs, and visualizations can be found in Cells 6-8 of the notebook.

## 📄 Report & Presentation
- A comprehensive report (`report.pdf`) details the debugging process, methodological modifications, and final conclusions.
- A presentation video provides a walkthrough of the entire project.
```
