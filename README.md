# CLIPByte

**CLIPByte** is a **tokenizer-free image captioning framework** that connects CLIP visual representations to a **ByT5 byte-level decoder** through a lightweight residual projection bridge.

### Key Contributions

* **Tokenizer-free captioning:** Generates captions directly as **UTF-8 bytes**, eliminating the need for a learned subword tokenizer.
* **CLIP–ByT5 integration:** Connects CLIP visual representations to ByT5 through a lightweight **residual projection bridge**.
* **Multilingual and script-agnostic generation:** Uses a single byte-level output interface for English and multilingual captioning without language-specific tokenization.
* **Efficient adaptation:** Explores parameter-efficient training while maintaining a lightweight vision-to-text connection.

### Evaluation

CLIPByte is evaluated on **English and multilingual image-captioning benchmarks** using standard captioning metrics, including **BLEU, METEOR, ROUGE-L, CIDEr, and SPICE**.

The experiments also investigate the individual contributions of **byte-level decoding** and the **residual projection bridge**.

### Status

**Research manuscript in preparation — not yet published.**

### Technologies

Python · PyTorch · Hugging Face Transformers · CLIP · ByT5 · LoRA · CUDA
