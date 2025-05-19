# 🧪 LLM Eval Playground

This project demonstrates how to evaluate and compare outputs from different Large Language Models (LLMs) using structured scoring methods — including factuality, clarity, and verbosity.

It complements my [LLM Evaluation Toolkit](https://github.com/epaunova/LLM-Evaluation-Toolkit), which provides a configurable scoring pipeline powered by GPT-based auto-grading.

---

## 🎯 Objective

Help Product Managers, ML engineers, and researchers:

- Compare LLM responses across models and prompts
- Visualize differences in output quality
- Experiment with evaluation strategies in real-world tasks

---

## 📂 Structure

llm-eval-playground/
├── notebooks/ # Jupyter Notebooks for experimentation
│ └── example_eval_comparison.ipynb
├── data/ # Sample prompts and model responses
├── outputs/ # Evaluation results and visual charts
├── utils/ # Optional helper scripts
└── README.md

yaml
Copy
Edit

---

## 📓 Example Notebook

📍 [`example_eval_comparison.ipynb`](notebooks/example_eval_comparison.ipynb)

In this notebook, we:

- Compare GPT-4 vs Mistral responses on 3 prompts  
- Score outputs on:
  - ✅ Factuality  
  - ✅ Clarity  
  - ✅ Verbosity
- Visualize results using `matplotlib`

🧪 *Note: This notebook uses mock data to demonstrate evaluation structure and visual analysis.*

---

## 📊 Sample Charts

Below are comparisons between GPT-4 and Mistral across three evaluation metrics:

![Factuality](https://github.com/epaunova/llm-eval-playground/raw/main/outputs/factuality_comparison.png)
![Clarity](https://github.com/epaunova/llm-eval-playground/raw/main/outputs/clarity_comparison.png)
![Verbosity](https://github.com/epaunova/llm-eval-playground/raw/main/outputs/verbosity_comparison.png)


---

## 🔧 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/epaunova/llm-eval-playground.git
   cd llm-eval-playground
Open the notebook:

bash
Copy
Edit
cd notebooks
jupyter notebook example_eval_comparison.ipynb
(Optional) Connect with the LLM Evaluation Toolkit to run real GPT-based scoring.

🌐 Author
👤 Eva Paunova
🔗 LinkedIn
📂 Portfolio

🚀 Coming Next
Integration with actual GPT evals (via OpenAI API)

More prompt types and output evaluation

Token-level and latency benchmarks
