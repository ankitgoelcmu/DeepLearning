# DeepLearning

A collection of Colab notebooks documenting my deep learning study path — from RNN/transformer fundamentals through building and fine-tuning models from scratch.

## Notebooks

| Notebook | Description |
|---|---|
| [DeepLearning_Concepts.ipynb](DeepLearning_Concepts.ipynb) | Notes on RNN fundamentals — sequential processing, hidden state, and the vanishing gradient problem. |
| [Transformer_Learnings_and_Key_Concepts.ipynb](Transformer_Learnings_and_Key_Concepts.ipynb) | Study notes on "Attention Is All You Need" — RNN/LSTM limitations, positional encoding, self-attention, and multi-head attention. |
| [Understanding_GPT__Word_Positional_embedding.ipynb](Understanding_GPT__Word_Positional_embedding.ipynb) | Deep dive into word and positional embeddings — how discrete tokens become continuous vectors for transformer input. |
| [NanoGPT_02.ipynb](NanoGPT_02.ipynb) | Implementation walkthrough of a GPT-2 style architecture (NanoGPT). |
| [RNN_Model01.ipynb](RNN_Model01.ipynb) | Hands-on RNN model implementation. |
| [03_pytorch_computer_vision_exercises.ipynb](03_pytorch_computer_vision_exercises.ipynb) | PyTorch computer vision exercises, based on notebook 03 of the *Learn PyTorch for Deep Learning* course. |
| [Transformer_for_Image_Recognition_VIT_Paper_Implementation_Exercise.ipynb](Transformer_for_Image_Recognition_VIT_Paper_Implementation_Exercise.ipynb) | Replication of the Vision Transformer (ViT) paper — "An Image Is Worth 16x16 Words." |
| [Fine_Tuning_Base_Model_PEFT_(QLORA).ipynb](Fine_Tuning_Base_Model_PEFT_(QLORA).ipynb) | Fine-tunes DistilBERT with QLoRA for network intrusion (threat) detection on the NSL-KDD dataset, converting tabular features into log-like text strings. |

## Usage

Each notebook has an "Open in Colab" badge and is self-contained — open it directly in Google Colab to run.

## Where this goes next

- **QLoRA notebook**: write up what the fine-tuned model gets right and wrong, and update intro notes that still mention DistilBERT (switched to BERT-base partway through).
- Add a KV cache to NanoGPT's text generation and measure the speedup.
- Fine-tune a small generative model (not just an encoder) with LoRA and compare it to prompting.

## Related

I use this foundation for building production AI agents. Those projects are in [agentic-ai](https://github.com/ankitgoelcmu/agentic-ai).
