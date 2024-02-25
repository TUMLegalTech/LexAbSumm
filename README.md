# LexAbSumm

# Dataset Card for LexAbSumm
LexAbSumm dataset is available on Huggingface:

[MahmoudAly/LexAbSumm](https://huggingface.co/datasets/MahmoudAly/LexAbSumm)

```python
from datasets import load_dataset
dataset = load_dataset("MahmoudAly/LexAbSumm")
```

### Dataset Summary

Legal professionals frequently encounter long legal judgments that hold critical insights for their work. While recent advances have led to automated summarization solutions for legal documents, they typically provide generic summaries, which may not meet the diverse information needs of users. To address this gap, we introduce LexAbSumm, a novel dataset designed for aspect-based summarization of legal case decisions, sourced from the European Court of Human Rights jurisdiction. We evaluate several abstractive summarization models tailored for longer documents on LexAbSumm, revealing a challenge in conditioning these models to produce aspect-specific summaries. We release LexAbSum to facilitate research in aspect-based summarization for legal domain.

### Languages

English

### Citation Information
