🧠 LLM from Scratch + Instruction Fine-Tuning + Spam Classifier

This repository contains educational and research-oriented projects focused on building and fine-tuning Language Models from scratch using GPT-2 weights. It includes three major components:

📂 Project Structure

<pre> <code> 📦 LLM Projects Repository ├── datasets/ │ ├── SMSSpamCollection │ ├── instruction-data.json │ └── the-verdict.txt │ ├── llm_from_scratch.ipynb ├── spam_classifier_from_scratch.ipynb ├── LLM_instruction_finetuning_from_scratch.ipynb └── README.md </code> </pre>

📌 Contents

1. 🔧 LLM from Scratch (llm_from_scratch.ipynb)
- Implements a basic LLM architecture (Transformer-based) from scratch.
- Tokenization logic using a Byte Pair Encoding (BPE) tokenizer built from the-verdict.txt.
- Handles out-of-vocabulary tokens and uses [endoftext].
- No pretrained model used here — pure educational implementation.

2. 🛡️ Spam Classifier using LLM (spam_classifier_from_scratch.ipynb)
- Fine-tunes GPT-2 weights on a binary SMS spam classification task.
- Dataset: SMSSpamCollection
- Converts classification problem into an instruction-based generation task.
- Demonstrates how a generative model can be adapted for classification.

3. 📖 Instruction Fine-Tuning (LLM_instruction_finetuning_from_scratch.ipynb)
- Uses instruction-data.json to fine-tune GPT-2 for instruction-following tasks.
- Aligns GPT-2 with prompt-based input/output formats.
- Prepares the model to follow commands more reliably — similar to how ChatGPT was aligned using instruction datasets.

📁 Datasets

All datasets are located in the datasets/ folder:
- SMSSpamCollection – For spam classification.
- instruction-data.json – Contains input/output pairs for instruction fine-tuning.
- the-verdict.txt – Used to build a BPE tokenizer vocabulary.

🧠 Goals

- Understand the internal architecture of LLMs by building from scratch.
- Explore how GPT-2 can be used for downstream tasks like classification.
- Experiment with instruction tuning to align models toward following user prompts.

🚀 Future Work

- Add support for multi-class classification.
- Improve BPE tokenizer with additional pre-tokenization rules.
- Instruction fine-tuning with larger instruction datasets like Self-Instruct or FLAN.

💡 Acknowledgements

- Inspired by GPT-2 architecture and Hugging Face models.
- Data credits: UCI, OpenAI (for model inspiration).

📬 Contact

Feel free to reach out via GitHub Issues for questions, suggestions, or collaborations.
