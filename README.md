In this project, I am doing a replication of the GPT language model (GPT-2 Small with 124 million parameters) from the ground up using PyTorch, covering all major components of a modern transformer-based large language model (LLM) such as multi-head self-attention, feedforward neural networks, layer normalization, residual connections, and causal masking for autoregressive text generation.

The model architecture includes 12 transformer blocks, each with 12 attention heads and an embedding dimension of 768, closely following the original GPT-2 (124M) configuration described by OpenAI. This replication aims to provide a transparent, end-to-end understanding of how generative transformers operate — from tokenization and training loop design to inference and text sampling — while maintaining code readability and modularity for exploration or educational use.

The implementation follows the principles outlined in Sebastian Raschka’s “Building LLMs from Scratch”.
