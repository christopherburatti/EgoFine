# EgoFine
This is the official implementation of the paper: "_EgoFine: an Ego Network-Based Approach to Fine-Tune Large Language Models from Knowledge Graphs_"

## Abstract
In recent years, Large Language Models (LLMs) have deeply influenced Natural Language
Processing, achieving outstanding results in various tasks. However, despite their impressive per-
formance, they sometimes produce hallucinations, which limits their reliability, especially in cer-
tain application fields. A promising research direction to mitigate these problems is to augment
LLMs with external structured knowledge, in particular Knowledge Graphs (KGs). While several
approaches have been proposed to combine LLMs and KGs, only few explore the possibility of fine-
tuning LLMs using knowledge stored in KGs, for example by exploiting local substructures of them.
In this paper, we present EgoFine, a new approach for fine-tuning LLMs based on ego networks
extracted from KGs. EgoFine identifies the most informative nodes in the KG using degree cen-
trality, extracts their ego networks, and generates structured training data through random paths
within them, thus enabling LLMs to learn domain-specific knowledge. Extensive experiments on
three KGs and two LLMs show that EgoFine consistently outperforms traditional embedding-based
methods and baseline fine-tuning strategies on all evaluation metrics, confirming its effectiveness
for fine-tuning LLMs through knowledge graph completion.

EgoFine's workflow is shown in <a href="#fig1">Figure 1</a>.
<a name="fig1">![image](https://github.com/user-attachments/assets/1da75fb5-e690-4b10-8ed4-840ed0227bd4)</a>
