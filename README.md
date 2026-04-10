# Transformer Architecture

A hands-on exploration of the Transformer architecture from the "Attention Is All You Need" paper. This notebook walks through each building block of the Transformer, with code and notes explaining how the pieces fit together.

## What's Covered

- **Self-Attention Mechanism** — how queries, keys, and values work to let the model focus on relevant parts of the input
- **Multi-Head Attention** — running multiple attention heads in parallel for richer representations
- **Positional Encoding** — injecting sequence order information since Transformers have no built-in notion of position
- **Feed-Forward Networks** — the point-wise fully connected layers within each block
- **Encoder-Decoder Structure** — how the full architecture comes together for sequence-to-sequence tasks
- **Layer Normalization & Residual Connections** — stabilizing training in deep networks

## File

- `TranformerArchitecture.ipynb` — Jupyter notebook with annotated code and explanations

## Why This Exists

Understanding Transformers at the implementation level is essential for anyone working with modern NLP. This notebook serves as a personal reference and learning resource built while studying the original paper and its components.

## Key References

- Vaswani et al., "Attention Is All You Need" (2017)
- Jay Alammar's "The Illustrated Transformer"

## Tech Stack

`Python` `PyTorch` `NumPy` `Jupyter`

## License

MIT
