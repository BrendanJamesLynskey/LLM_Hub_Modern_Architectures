# Modern Architectures

Architectures beyond the vanilla decoder &mdash; Mixture-of-Experts, Mamba and state-space models, long-context techniques, diffusion language models, hybrids.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_Modern_Architectures/

## Presentations in this series

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Mixture of Experts](https://brendanjameslynskey.github.io/Arch_01_MoE/) | live | Total params vs active params; Switch routing; Mixtral; DeepSeek-V3 fine-grained &amp; shared experts; load balance loss; expert parallelism; training pitfalls. |
| 02 | [Mamba &amp; State-Space Models](https://brendanjameslynskey.github.io/Arch_02_Mamba_SSM/) | live | S4 / HIPPO origins, Mamba selective SSM, Mamba-2 / SSD duality with attention; RWKV; where SSMs win and where they lose vs attention. |
| 03 | [Long-Context Techniques](https://brendanjameslynskey.github.io/Arch_03_Long_Context/) | live | RoPE, position interpolation, NTK-aware, YaRN, ALiBi, sliding window + sink tokens (StreamingLLM), ring attention, context parallelism. |
| 04 | [Diffusion Language Models](https://brendanjameslynskey.github.io/Arch_04_Diffusion_LMs/) | live | SEDD score-based discrete diffusion, LLaDA masking, mask-prediction schedules, parallel decoding trade-offs, where diffusion may win for code &amp; structured outputs. |
| 05 | [Hybrid &amp; Encoder-Decoder](https://brendanjameslynskey.github.io/Arch_05_Hybrid_and_Encoder_Decoder/) | live | Jamba, Zamba; T5 / FLAN-T5; when encoder-decoder beats decoder-only; byte-level (ByT5); architecture-selection decision tree. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
