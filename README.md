# 🧠 Generative Agents for Crowdsourced Fact-Checking

This repository contains the code and experimental assets for the paper **[Assessing the Potential of Generative Agents in Crowdsourced Fact-Checking](https://arxiv.org/abs/2504.19940)**.

## ✨ Overview

This project introduces a novel framework that simulates the **crowdsourced fact-checking process** using **generative agents**—autonomous entities powered by large language models (LLMs). Inspired by human-based crowd systems like *Community Notes*, our framework emulates the diversity of real-world evaluators through synthetic agents equipped with realistic **demographic** and **ideological profiles**.

The key idea:

> Can synthetic crowds replicate or even outperform human fact-checkers in assessing the veracity of online claims?

## 🧩 Key Features

* 🔁 **Protocol Replication**
  Mirrors the experimental design of [La Barbera et al., 2024](https://www.sciencedirect.com/science/article/pii/S0306457324001523), enabling direct human vs. agent comparison.

* 👥 **Demographically Grounded Agents**
  Agents are instantiated with real-world demographic and political profiles derived from human participants.

* 🔎 **Evidence Selection**
  Each agent selects the most relevant web page from a curated list, using summaries generated via LLMs.

* 🧾 **Multi-dimensional Evaluation**
  Agents complete the same structured questionnaire as human annotators, rating claims across 6 quality dimensions (e.g., *accuracy*, *unbiasedness*, *completeness*, etc.) and issuing a final veracity judgment.

* 📊 **Cross-Model Evaluation**
  Benchmarks across 3 LLMs: **LLaMA 3.1 8B**, **Gemma 2 9B**, and **Mistral 7B**, evaluating effectiveness, consistency, and bias sensitivity.

* 📚 **Reproducibility First**
  All prompts, experimental configurations, and data splits are included for full transparency.

## 📈 Results Summary

Generative agents:

* Achieve **higher agreement with expert annotations** than human crowds.
* Demonstrate **greater internal consistency** across evaluative dimensions.
* Show **reduced sensitivity to demographic and ideological bias**.

## 📬 Contact

For questions or collaborations, feel free to open an issue or contact [Gian Marco Orlando](mailto:gianmarco.orlando@unina.it)
