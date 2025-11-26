# AWQ-4bits-on-small-LLMs
This repo tries to implement Activation-aware Weight Quantization for LLM Compression and Acceleration from scratch and apply it on small LLMs and assess performance degradation
## References

- **AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration**  
  *by Linjian Ma, Zhengyan Zhang, Yixiao Ge, et al.*  
  arXiv: https://arxiv.org/abs/2306.00978
This work is for educational purposes .
The Layout is as follows:
- We show why naive weight only quantization is harmful for LLMs by perplexity measures
- We perform quantization while preserving "important" weights in full precision.
- We scale important weight channels and see how it affects perplexity.
- perform activation aware weight only quantization and see the resutls .
This is an aim of reproducing an already established observation but implemented all by me .
