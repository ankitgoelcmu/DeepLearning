# DeepLearning

Notebooks from working through deep learning fundamentals — RNNs, transformers, and building/fine-tuning models by hand instead of just calling an API.

## Notebooks

### Highlights

| Notebook | Description |
|---|---|
| [NanoGPT_02.ipynb](NanoGPT_02.ipynb) | Building a GPT-2 style model from scratch. |
| [Transformer_for_Image_Recognition_VIT_Paper_Implementation_Exercise.ipynb](Transformer_for_Image_Recognition_VIT_Paper_Implementation_Exercise.ipynb) | Replicating the Vision Transformer paper ("An Image Is Worth 16x16 Words"). |
| [Fine_Tuning_Base_Model_PEFT_(QLORA).ipynb](Fine_Tuning_Base_Model_PEFT_(QLORA).ipynb) | Fine-tuning BERT-base with QLoRA to do threat detection on the NSL-KDD network intrusion dataset — turning tabular log features into text so a language model can classify them. |

### Foundations

| Notebook | Description |
|---|---|
| [DeepLearning_Concepts.ipynb](DeepLearning_Concepts.ipynb) | RNN basics — how hidden state works, and why vanishing gradients kill long-range memory. |
| [Transformer_Learnings_and_Key_Concepts.ipynb](Transformer_Learnings_and_Key_Concepts.ipynb) | Notes from working through "Attention Is All You Need" — self-attention, multi-head attention, positional encoding. |
| [Understanding_GPT__Word_Positional_embedding.ipynb](Understanding_GPT__Word_Positional_embedding.ipynb) | How tokens turn into embeddings, and why position has to be encoded separately. |
| [RNN_Model01.ipynb](RNN_Model01.ipynb) | An RNN built from scratch. |
| [03_pytorch_computer_vision_exercises.ipynb](03_pytorch_computer_vision_exercises.ipynb) | Computer vision exercises from the *Learn PyTorch for Deep Learning* course. |

## Usage

Every notebook has an "Open in Colab" badge — click it and run.

## Where this goes next

- **QLoRA notebook**: write up what the fine-tuned model actually gets right and wrong, and fix the intro text — it still says DistilBERT, but I switched to BERT-base partway through.
- Add a KV cache to NanoGPT's text generation and see how much faster it gets.
- Fine-tune a small generative model (not just an encoder) with LoRA and compare it against just prompting.

## Related

This is the foundation I build production AI agents on top of — that work lives in [agentic-ai](https://github.com/ankitgoelcmu/agentic-ai).
