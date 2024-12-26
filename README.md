# Counter-Narrative Generation for Spanish Hate Speech

## Overview
This project addresses the growing concern of hate speech in Spanish-speaking communities by generating counter-narratives (CNG) as constructive responses. These counter-narratives aim to de-escalate hostility, promote empathy, and foster understanding. Using advanced Natural Language Processing (NLP) techniques, the project leverages transformer-based models, such as M-BART and MT5, fine-tuned on curated datasets of Spanish hate speech paired with counter-narratives.


## Key Features
- **Transformer Models**: Utilizes state-of-the-art models like MBART and MT5 for generating context-aware and culturally sensitive counter-narratives.
- **Sentiment Analysis**: Analyzes linguistic and emotional tones of hate speech to tailor effective responses.
- **Customizable**: Easily adaptable to different languages and cultural nuances.
- **Evaluation**: Employs BLEU, ROUGE, and BERTScore metrics for performance assessment.

## Getting Started

### Prerequisites
- Python 3.8 or later
- Google Cloud credentials for Vertex AI integration


## Methodology
1. **Dataset**: Fine-tuned on datasets containing Spanish hate speech paired with counter-narratives. Features include:
   - Hate Speech Types (e.g., personal attack, discrimination).
   - Counter-Narrative Types (e.g., factual correction, empathy).
2. **Preprocessing**: Text cleaning, tokenization, and normalization to enhance linguistic and cultural sensitivity.
3. **Modeling**:
   - **MBART**: Excels in text generation with a focus on coherence.
   - **MT5**: Multilingual support with fine-tuning for Spanish nuances.
4. **Evaluation**:
   - **Quantitative**: BLEU, ROUGE, and BERTScore metrics.
   - **Qualitative**: Human evaluation of relevance, fluency, and constructiveness.

## Results
## Comparative Analysis of BART-large and mT5-base Models on a Spanish Dataset

### Model Overview

- **BART-large**: Known for its effectiveness in text generation, utilizing a bidirectional encoder and autoregressive decoder.
- **mT5-base**: A versatile multilingual model adapted from T5, designed to handle text-to-text tasks in multiple languages including Spanish.

### Performance Evaluation

- **Accuracy**:
  - **BART-large** showed superior performance on the Spanish dataset, indicating its robust capacity for generating coherent and contextually appropriate Spanish text.
  - **mT5-base**, while effective in multilingual settings, was slightly less accurate than BART-large when evaluated solely on Spanish.

- **Speed**:
  - **BART-large** provided faster responses, which is advantageous for real-time applications in Spanish.
  - **mT5-base** exhibited longer processing times, potentially due to its generalized multilingual architecture.

- **Resource Usage**:
  - **BART-large** required more computational resources per inference, which is a consideration for deployment in resource-limited environments.
  - **mT5-base** maintained better efficiency in resource usage, beneficial for large-scale or multilingual deployments.

### Observations

- BART-large is recommended for projects where high accuracy and quick response times are critical in Spanish language tasks, despite higher resource consumption.
- mT5-base is suitable for projects that demand versatility across languages and are sensitive to computational resource constraints, though with a slight compromise on speed and accuracy for Spanish.

### Recommendations for Improvement

1. **Optimization**: Explore model compression techniques such as quantization for BART-large to enhance deployment efficiency without significantly impacting performance.
2. **Fine-tuning**: Increase the Spanish language corpus for mT5-base to narrow the performance gap with BART-large in specific linguistic contexts.
3. **Evaluation Metrics Expansion**: Include more nuanced metrics like grammatical accuracy and idiomatic expression to better assess model performance in generating Spanish text.

