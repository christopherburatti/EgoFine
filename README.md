# EgoFine
This is the official implementation of the paper: "_EgoFine: an Ego Network-Based Approach to Fine-Tune Large Language Models from Knowledge Graphs_"

## Abstract
In recent years, Large Language Models (LLMs) have deeply influenced Natural Language
Processing, achieving outstanding results in various tasks. However, despite their impressive performance,
they sometimes produce hallucinations, which limits their reliability, especially in certain
application fields. A promising research direction to mitigate these problems is to augment
LLMs with external structured knowledge, in particular Knowledge Graphs (KGs). While several
approaches have been proposed to combine LLMs and KGs, only few explore the possibility of finetuning
LLMs using knowledge stored in KGs, for example exploiting local substructures derived
from them. In this paper, we present EgoFine, a new approach for fine-tuning LLMs based on
ego networks extracted from KGs. EgoFine identifies the most informative nodes in the KG using
degree centrality, extracts their ego networks, and generates structured training data through
random paths within them, thus enabling LLMs to learn domain-specific knowledge. Extensive
experiments on three KGs and two LLMs show that EgoFine consistently outperforms traditional
embedding-based methods and baseline fine-tuning strategies on all evaluation metrics, confirming
its effectiveness for fine-tuning LLMs through KG completion.

EgoFine's workflow is shown in <a href="#fig1">Figure 1</a>.
<a name="fig1">![image](https://github.com/user-attachments/assets/1da75fb5-e690-4b10-8ed4-840ed0227bd4)</a>

## Repository structure
This repository can be directly downloaded and executed locally.

We provide the datasets used and the implementation code for both the proposed approach and the LLM baseline.

> [!NOTE]  
> You need to uncomment some parts of the code depending on the chosen dataset.
