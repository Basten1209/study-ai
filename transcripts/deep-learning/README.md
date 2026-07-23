# MIT 6.7960 Deep Learning, Fall 2024 Transcripts

Source: https://notebooklm.google.com/notebook/1974010f-eec5-485b-b074-000c70149926
Extracted: 2026-07-02

These files contain text extracted from the NotebookLM source viewer.

- Sources 1-24 are lecture video transcripts. NotebookLM lists `Lec 05. Architectures: Graphs` twice; both entries are preserved and their transcript text is identical.
- Source 25 is the YouTube playlist page text, not a lecture transcript.
- Source 26 is the PyTorch Tutorial transcript.

## Proofread transcripts

Proofread editions preserve the lecture order and substantive Q&A while correcting ASR errors, technical notation, and speaker labels. Editorial notes identify factual issues in the spoken lecture instead of silently changing them.

| Lecture | Raw ASR | Proofread transcript | Validation sources |
| ------- | ------- | -------------------- | ------------------ |
| Lec 12. Representation Learning: Similarity-Based | [raw](./source-13-lec-12-representation-learning-similarity-based.md) | [proofread](./proofread/source-13-lec-12-representation-learning-similarity-based.md) | [MIT OCW video](https://ocw.mit.edu/courses/6-7960-deep-learning-fall-2024/resources/mit6_7960f24_lec12_mp4/), [speaker transcript](https://ocw.mit.edu/courses/6-7960-deep-learning-fall-2024/1l8PjEaaBW_2_khhxnZawcrBEZsfbuLO2_transcript.pdf), [slides](https://ocw.mit.edu/courses/6-7960-deep-learning-fall-2024/mit6_7960_f24_lec12.pdf), [Xing et al.](https://papers.nips.cc/paper_files/paper/2002/hash/c3e4035af2a1cde9f21e1ae1951ac80b-Abstract.html), [SimCLR](https://proceedings.mlr.press/v119/chen20j.html), [Wang–Isola](https://proceedings.mlr.press/v119/wang20k.html), [MoCo](https://arxiv.org/abs/1911.05722), [iNaturalist 2021](https://openaccess.thecvf.com/content/CVPR2021/html/Van_Horn_Benchmarking_Representation_Learning_for_Natural_World_Image_Collections_CVPR_2021_paper.html), [Cole et al.](https://openaccess.thecvf.com/content/CVPR2022/html/Cole_When_Does_Contrastive_Visual_Representation_Learning_Work_CVPR_2022_paper.html) |

| # | Source | Transcript | Characters |
| - | ------ | ---------- | ---------- |
| 1 | Lec 01. Introduction to Deep Learning | [source-01-lec-01-introduction-to-deep-learning.md](./source-01-lec-01-introduction-to-deep-learning.md) | 58201 |
| 2 | Lec 02. How to Train a Neural Net | [source-02-lec-02-how-to-train-a-neural-net.md](./source-02-lec-02-how-to-train-a-neural-net.md) | 69893 |
| 3 | Lec 03. Approximation Theory | [source-03-lec-03-approximation-theory.md](./source-03-lec-03-approximation-theory.md) | 71113 |
| 4 | Lec 04. Architectures: Grids | [source-04-lec-04-architectures-grids.md](./source-04-lec-04-architectures-grids.md) | 79279 |
| 5 | Lec 05. Architectures: Graphs | [source-05-lec-05-architectures-graphs.md](./source-05-lec-05-architectures-graphs.md) | 76419 |
| 6 | Lec 05. Architectures: Graphs | [source-06-lec-05-architectures-graphs-2.md](./source-06-lec-05-architectures-graphs-2.md) | 76419 |
| 7 | Lec 06. Generalization Theory | [source-07-lec-06-generalization-theory.md](./source-07-lec-06-generalization-theory.md) | 76788 |
| 8 | Lec 07. Scaling Rules for Optimization | [source-08-lec-07-scaling-rules-for-optimization.md](./source-08-lec-07-scaling-rules-for-optimization.md) | 67246 |
| 9 | Lec 08. Architectures: Transformers | [source-09-lec-08-architectures-transformers.md](./source-09-lec-08-architectures-transformers.md) | 72407 |
| 10 | Lec 09. Hacker's Guide to Deep Learning | [source-10-lec-09-hackers-guide-to-deep-learning.md](./source-10-lec-09-hackers-guide-to-deep-learning.md) | 76133 |
| 11 | Lec 10. Architectures: Memory | [source-11-lec-10-architectures-memory.md](./source-11-lec-10-architectures-memory.md) | 67121 |
| 12 | Lec 11. Representation Learning: Reconstruction-Based | [source-12-lec-11-representation-learning-reconstruction-based.md](./source-12-lec-11-representation-learning-reconstruction-based.md) | 82090 |
| 13 | Lec 12. Representation Learning: Similarity-Based | [source-13-lec-12-representation-learning-similarity-based.md](./source-13-lec-12-representation-learning-similarity-based.md) | 70293 |
| 14 | Lec 13. Representation Learning: Theory | [source-14-lec-13-representation-learning-theory.md](./source-14-lec-13-representation-learning-theory.md) | 59908 |
| 15 | Lec 14. Generative Models: Basics | [source-15-lec-14-generative-models-basics.md](./source-15-lec-14-generative-models-basics.md) | 78267 |
| 16 | Lec 15. Generative Models: Representation Learning Meets Generative Modeling | [source-16-lec-15-generative-models-representation-learning-meets-generative-modeling.md](./source-16-lec-15-generative-models-representation-learning-meets-generative-modeling.md) | 74067 |
| 17 | Lec 16. Generative Models: Conditional Models | [source-17-lec-16-generative-models-conditional-models.md](./source-17-lec-16-generative-models-conditional-models.md) | 78114 |
| 18 | Lec 17. Generalization: Out-of-Distribution (OOD) | [source-18-lec-17-generalization-out-of-distribution-ood.md](./source-18-lec-17-generalization-out-of-distribution-ood.md) | 61784 |
| 19 | Lec 18. Transfer Learning: Models | [source-19-lec-18-transfer-learning-models.md](./source-19-lec-18-transfer-learning-models.md) | 82111 |
| 20 | Lec 19. Transfer Learning: Data | [source-20-lec-19-transfer-learning-data.md](./source-20-lec-19-transfer-learning-data.md) | 72827 |
| 21 | Lec 20. Scaling Laws | [source-21-lec-20-scaling-laws.md](./source-21-lec-20-scaling-laws.md) | 35789 |
| 22 | Lec 21. Language Models | [source-22-lec-21-language-models.md](./source-22-lec-21-language-models.md) | 79591 |
| 23 | Lec 23. Metrized Deep Learning | [source-23-lec-23-metrized-deep-learning.md](./source-23-lec-23-metrized-deep-learning.md) | 58633 |
| 24 | Lec 24. Inference Methods for Deep Learning | [source-24-lec-24-inference-methods-for-deep-learning.md](./source-24-lec-24-inference-methods-for-deep-learning.md) | 82478 |
| 25 | MIT 6.7960 Deep Learning, Fall 2024 - YouTube | [source-25-mit-6-7960-deep-learning-fall-2024-youtube.md](./source-25-mit-6-7960-deep-learning-fall-2024-youtube.md) | 4220 |
| 26 | PyTorch Tutorial | [source-26-pytorch-tutorial.md](./source-26-pytorch-tutorial.md) | 26283 |
