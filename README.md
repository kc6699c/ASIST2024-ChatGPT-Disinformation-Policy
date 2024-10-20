# ASIST2024-ChatGPT-Disinformation-Policy

# ASIST2024-ChatGPT-Disinformation-Policy

This repository accompanies the research paper:  
**"Are Prompts All You Need? Chatting with ChatGPT on Disinformation Policy Understanding"**  
Presented at the **87th Annual Meeting of the Association for Information Science & Technology (ASIS&T), Calgary, Canada, Oct. 25 – 29, 2024**.

[![Read the Paper](https://www.researchgate.net/publication/384950923_Are_Prompts_All_You_Need_Chatting_with_ChatGPT_on_Disinformation_Policy_Understanding)](https://www.researchgate.net/publication/384950923_Are_Prompts_All_You_Need_Chatting_with_ChatGPT_on_Disinformation_Policy_Understanding)

---

## Overview
This project explores the use of **ChatGPT** for the **automatic analysis of disinformation policy documents**, employing **zero-shot** and **few-shot learning strategies** through prompt engineering. The study aims to address three primary research questions:
1. Can ChatGPT effectively analyze policy documents?
2. How can prompts be optimized for better automatic policy understanding?
3. What practices improve ChatGPT’s performance in policy content analysis?

The project focuses on identifying five key policy components:  
**Context, Actors, Issues, Instruments, and Channels**.

---

## Repository Structure




Overview of the project, including objectives, problem statement, and brief explanation of methodologies.
Instructions on how to run experiments (e.g., setting up ChatGPT prompts).
Contact information for further questions.
[![Paper Link](https://www.researchgate.net/publication/384950923_Are_Prompts_All_You_Need_Chatting_with_ChatGPT_on_Disinformation_Policy_Understanding)]
/data/

A subset of the 37 policy documents or sample documents (if public sharing of the original documents is restricted).
Processed data used for zero-shot and few-shot experiments.
/code/

Python scripts or notebooks containing:
Prompt engineering process (zero-shot and few-shot).
Code for loading, preprocessing, and evaluating policy content.
Accuracy and F-score calculations comparing ChatGPT's outputs with manual labels.
/prompts/

Separate files for each prompt strategy used (P1 to P6):
P1 to P2: Zero-shot learning prompts.
P3 to P6: Few-shot learning with expert definitions, annotated data, and ChatGPT-generated unique aspects.
/results/

Evaluation metrics and results (accuracy, F-score) for the different experiments (tabular data as presented in the paper).
Include graphs or tables showing the progression of accuracy and F-score across trials.
