Overview

This repository contains two key files related to political stance detection in socio-political contexts using structured knowledge graphs and chain-of-questions reasoning:

bpdisc.xlsx – A dataset containing politically charged tweets from Bangladesh during and after the July 2024 protests.

grasp-choq.ipynb – A Jupyter Notebook implementing the GRASP-ChoQ model for political stance detection.

File Descriptions

1. bpdisc.xlsx

BPDisC (Bangladesh Political Discourse Corpus) is a novel dataset designed to analyze political discussions on social media. It consists of:

Tweets related to political events in Bangladesh.

Annotations for political stance detection.

Metadata linking tweets to relevant political entities and events.

Information extracted to support contextual analysis with a knowledge graph.

2. grasp-choq.ipynb

The Jupyter Notebook implements GRASP-ChoQ (Graph-Assisted Structured Prediction using Chain-of-Questions), a method for political stance detection. This approach:

Utilizes a knowledge graph to provide contextual understanding of political discourse.

Employs a chain-of-questions reasoning process to break down interactions in political texts.

Moves away from direct stance predictions and instead follows intermediate reasoning steps.

Improves retrieval augmentation, enabling adaptive analysis of political discussions in low-resource settings.

Key Highlights from the Experiment:

GRASP-ChoQ demonstrated significant performance improvements over baseline models.

Integration with the DeepSeek R1 variant led to a 40% higher F1 score compared to zero-shot detection.
