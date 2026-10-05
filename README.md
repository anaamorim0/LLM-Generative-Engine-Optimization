# LLM Generative Engine Optimization

Research project from my internship at **Wise Pirates** (Oct 2025 – Jan 2026), part of my B.Sc. in Computer Science at the University of Porto.

More and more people ask chatbots like ChatGPT for product recommendations instead of using a search engine. **Generative Engine Optimization (GEO)** studies how these models decide what to recommend. This project explores that question with open-source LLMs in a controlled, local environment.

> ⚠️ This was an exploratory research study, done only to understand how generative models behave. It was not used commercially.

## What I built

- **Two optimization strategies**, implemented in Python and compared:
  - **Gradient-based (Greedy Coordinate Gradient):** uses the model's gradients to find a short text sequence that pushes a target product up the recommendation list.
  - **Semantic optimization (beam search):** uses an LLM to rewrite the product description in natural, fluent language while scoring how well it ranks.
- **An evaluation pipeline** that sends the same user query thousands of times and measures how often, and in which position, the target product is recommended.
- **An interactive dashboard** (Dash/Plotly) to configure runs, follow optimization progress live and export results to Excel.

## Tech stack

Python · Llama 3.2 (1B & 3B) · Hugging Face · Ollama · NumPy · Pandas · Dash · Plotly · Matplotlib

## Code & results

The source code and detailed results are confidential and belong to Wise Pirates, so they aren't published here.
