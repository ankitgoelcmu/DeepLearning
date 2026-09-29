# DeepLearning

Notebooks from learning deep learning: RNNs, transformers, and building models by hand instead of just calling an API.

## Notebooks

### Highlights

| Notebook | Description |
|---|---|
| [NanoGPT_02.ipynb](NanoGPT_02.ipynb) | Building a GPT-2 style model in PyTorch, from tokenizer to training loop. |
| [Transformer_for_Image_Recognition_VIT_Paper_Implementation_Exercise.ipynb](Transformer_for_Image_Recognition_VIT_Paper_Implementation_Exercise.ipynb) | Rebuilding the Vision Transformer paper ("An Image Is Worth 16x16 Words"). |
| [Fine_Tuning_Base_Model_PEFT_(QLORA).ipynb](Fine_Tuning_Base_Model_PEFT_(QLORA).ipynb) | Fine-tuning BERT-base with QLoRA to spot network intrusions in the NSL-KDD dataset. Turns table rows into text so a language model can read them. |

### Foundations

| Notebook | Description |
|---|---|
| [DeepLearning_Concepts.ipynb](DeepLearning_Concepts.ipynb) | RNN basics: how hidden state works, and why vanishing gradients wipe out long-term memory. |
| [Transformer_Learnings_and_Key_Concepts.ipynb](Transformer_Learnings_and_Key_Concepts.ipynb) | Notes from reading "Attention Is All You Need": self-attention, multi-head attention, positional encoding. |
| [Understanding_GPT__Word_Positional_embedding.ipynb](Understanding_GPT__Word_Positional_embedding.ipynb) | How tokens turn into embeddings, and why position has to be encoded separately. |
| [RNN_Model01.ipynb](RNN_Model01.ipynb) | Training an RNN sequence model end to end in PyTorch. |
| [03_pytorch_computer_vision_exercises.ipynb](03_pytorch_computer_vision_exercises.ipynb) | Computer vision exercises from the *Learn PyTorch for Deep Learning* course. |

## Usage

Every notebook has an "Open in Colab" badge. Click it and run.

## Where this goes next

- **QLoRA notebook**: write up what the model gets right and wrong.
- Add a KV cache to NanoGPT's text generation and see how much faster it gets.
- Fine-tune a small generative model (not just an encoder) with LoRA and compare it to just prompting.

## Related

I use this as the base for building AI agents. That work is in [agentic-ai](https://github.com/ankitgoelcmu/agentic-ai).
