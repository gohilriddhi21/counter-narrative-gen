# Counter-Narrative Generation for Spanish Hate Speech

## Overview
This project addresses the growing concern of hate speech in Spanish-speaking communities by generating counter-narratives (CNG) as constructive responses. These counter-narratives aim to de-escalate hostility, promote empathy, and foster understanding. Using advanced Natural Language Processing (NLP) techniques, the project leverages transformer-based models, such as BART and T5, fine-tuned on curated datasets of Spanish hate speech paired with counter-narratives.


## Key Features
- **Transformer Models**: Utilizes state-of-the-art models like BART and T5 for generating context-aware and culturally sensitive counter-narratives.
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
   - **BART**: Excels in text generation with a focus on coherence.
   - **T5**: Multilingual support with fine-tuning for Spanish nuances.
4. **Evaluation**:
   - **Quantitative**: BLEU, ROUGE, and BERTScore metrics.
   - **Qualitative**: Human evaluation of relevance, fluency, and constructiveness.

## Results
- **Performance**: Strong BLEU and ROUGE scores, with T5 slightly outperforming BART in generating context-aware counter-narratives.
- **Strengths**: Effective in generating empathetic and factual responses.
- **Challenges**: Edge cases such as nuanced humor and highly context-specific responses require further tuning.


