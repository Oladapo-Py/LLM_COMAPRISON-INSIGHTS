# 🔍 LLM Comparison Insights Dashboard

This project presents a data-driven comparison of over **200 Large Language Models (LLMs)**, analyzed and visualized using **Power BI**. It offers insights into performance, cost-efficiency, compute power, and model architecture (open-source vs proprietary) — helping developers, researchers, and businesses make informed decisions about which LLMs to adopt.

---

## 📌 Project Overview

With the growing variety of LLMs available, this project seeks to answer the following questions:

- How do open-source models compare to proprietary ones in terms of speed, cost, and efficiency?
- Which models offer the best value for specific applications like real-time chat or cost-sensitive deployment?
- What trade-offs exist between model **speed**, **cost per million tokens**, and **compute power**?
- Are older models like GPT-2 still viable options in today’s ecosystem?

---

## 🗃️ Dataset Summary

Each row in the dataset represents a unique model configuration and includes:
- Model provider and version
- Open-source vs proprietary classification
- Speed (tokens/sec), Latency (sec), Price per million tokens
- Compute power and energy efficiency metrics
- Benchmark scores: **MMLU** (academic reasoning) and **Chatbot Arena** (real-world ranking)
- Simplified ratings: Quality, Speed, Price

---

## ⚙️ Tools & Technologies

- **Power BI** for data modeling and dashboard visualization
- **CSV dataset** of 200 LLM configurations (synthetic/comparative data)
- Metrics analyzed: token speed, latency, cost, compute power, energy efficiency, training dataset size
- Dimensions compared: model type (open-source vs proprietary), provider, and benchmark scores

---

## 📈 Key Insights

- **LLaMA-5** and **Nova-7** deliver the best performance per price, offering top value for cost-conscious applications.
- **DeepSeek-6** and **Gemini-6** are among the fastest models, making them ideal for latency-sensitive tasks like real-time chat.
- **Open-source models** generally outperform proprietary models in **energy efficiency** and **latency**, though proprietary models tend to lead in benchmarks.
- **GPT-2** and **LLaMA-7**, while historically significant, are no longer competitive in terms of performance or cost.
- **Cohere** and **Google** offer the most powerful models in terms of compute usage, suitable for research and advanced AI workloads.

---

## ✅ Recommendations

- **Use LLaMA-5 or Nova-7** for cost-effective deployments where maximizing performance per dollar is essential. These models balance speed and affordability, making them well-suited for general-purpose applications like chatbots, internal tools, or educational AI features.

- **Deploy DeepSeek-6 or Gemini-6** in systems that demand fast processing, such as real-time assistants or summarization tools. These models offer high speed at relatively low cost, making them effective for time-sensitive or interactive platforms.

- **Choose open-source models** in environments where energy efficiency and compute limitations are critical, such as edge devices or cloud-deployment under resource constraints. Open-source models like LLaMA-5 provide flexibility without compromising much on performance.

- **Avoid legacy models** like GPT-2 and LLaMA-7 for new projects. These models have higher token costs and lower speeds, making them inefficient in comparison to more modern alternatives.

- **Adopt models from Cohere or Google** for compute-heavy, research-driven applications. These high-performing models are ideal for tasks such as academic NLP research, enterprise AI workflows, or multi-modal reasoning, where performance outweighs compute cost.

---

## 📊 Dashboard Highlights

- **Bar Charts** to rank models by cost, speed, and compute power
- **Line + Dual Axis Charts** to compare trade-offs between price and speed
- **Open vs Proprietary Comparison** by metrics like latency and energy efficiency

> 📁 *To view the full interactive dashboard or data model, please refer to the Power BI file in this repository.*

---


## 📬 Contact

For feedback, collaboration, or questions:

- LinkedIn: [Your Profile](https://www.linkedin.com/in/oladapo-lijadu)
- Twitter/X: [@yourhandle](https://twitter.com/Dapopy1)

---

## 📄 License

This project is open for educational and non-commercial use. Attribution is appreciated if shared or reused.

---

## 🌟 Star this repo if you found it helpful!

