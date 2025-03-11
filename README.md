# TimeLoc

<p align="left">
<a href="https://arxiv.org/abs/2503.06526" alt="arXiv">
    <img src="https://img.shields.io/badge/arXiv-2503.06526-b31b1b.svg?style=flat" /></a>
</p>

This is the official implementation of the paper [TimeLoc: A Unified End-to-End Framework for Precise Timestamp Localization in Long Videos](https://arxiv.org/abs/2503.06526).

# Abstract

Temporal localization in untrimmed videos, which aims to identify specific timestamps, is crucial for video understanding but remains challenging. This task encompasses several subtasks, including temporal action localization, temporal video grounding, moment retrieval, and generic event boundary detection. Existing methods in each subfield are typically designed for specific tasks and lack generalizability across domains. In this paper, we propose TimeLoc, a unified end-to-end framework for timestamp localization that can handle multiple tasks. First, our approach employs a simple yet effective one-stage localization model that supports text queries as input and multiple actions as output. Second, we jointly train the video encoder and localization model in an end-to-end manner. To efficiently process long videos, we introduce temporal chunking, enabling the handling of videos with over 30k frames. Third, we find that fine-tuning pre-trained text encoders with a multi-stage training strategy further enhances text-conditioned localization. TimeLoc achieves state-of-the-art results across multiple benchmarks.
