# Dialogue Summarization using Transformers

This project explores dialogue summarization using the **SAMSum dataset** and compares two Transformer-based approaches.

## Models

- **Custom Transformer:** Encoder-decoder architecture trained from scratch.
- **T5-small:** Pretrained model fine-tuned on SAMSum.

## Evaluation Results

Both models were evaluated on the same 819-example test set using ROUGE metrics.

| Metric | Custom Transformer | T5-small |
|---|---:|---:|
| ROUGE-1 | 0.1294 | **0.4660** |
| ROUGE-2 | 0.0211 | **0.2185** |
| ROUGE-L | 0.1090 | **0.3837** |

## Technologies

- Python
- TensorFlow
- Keras
- Hugging Face
- ROUGE

## Dataset

[ SAMSum Dataset – Hugging Face](https://huggingface.co/datasets/knkarthick/samsum)

## Objective

To explore encoder-decoder Transformers, understand transfer learning, and compare training from scratch with pretrained model fine-tuning.
