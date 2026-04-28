# Modern Architectures

Architectures beyond the vanilla decoder &mdash; Mixture-of-Experts, Mamba and state-space models, long-context techniques, diffusion language models, hybrids &mdash; plus a five-deck companion to Sebastian Raschka's *Beyond Standard LLMs* surveying linear-attention hybrids, text diffusion, code world models, and small recursive transformers.

**Live index:** https://brendanjameslynskey.github.io/LLM_Hub_Modern_Architectures/

## Presentations in this series

### Foundations &mdash; architectures beyond the vanilla decoder

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 01 | [Mixture of Experts](https://brendanjameslynskey.github.io/Arch_01_MoE/) | live | Total params vs active params; Switch routing; Mixtral; DeepSeek-V3 fine-grained &amp; shared experts; load balance loss; expert parallelism; training pitfalls. |
| 02 | [Mamba &amp; State-Space Models](https://brendanjameslynskey.github.io/Arch_02_Mamba_SSM/) | live | S4 / HIPPO origins, Mamba selective SSM, Mamba-2 / SSD duality with attention; RWKV; where SSMs win and where they lose vs attention. |
| 03 | [Long-Context Techniques](https://brendanjameslynskey.github.io/Arch_03_Long_Context/) | live | RoPE, position interpolation, NTK-aware, YaRN, ALiBi, sliding window + sink tokens (StreamingLLM), ring attention, context parallelism. |
| 04 | [Diffusion Language Models](https://brendanjameslynskey.github.io/Arch_04_Diffusion_LMs/) | live | SEDD score-based discrete diffusion, LLaDA masking, mask-prediction schedules, parallel decoding trade-offs, where diffusion may win for code &amp; structured outputs. |
| 05 | [Hybrid &amp; Encoder-Decoder](https://brendanjameslynskey.github.io/Arch_05_Hybrid_and_Encoder_Decoder/) | live | Jamba, Zamba; T5 / FLAN-T5; when encoder-decoder beats decoder-only; byte-level (ByT5); architecture-selection decision tree. |

### Companion to Sebastian Raschka &mdash; *Beyond Standard LLMs*

A five-deck companion to [Sebastian Raschka's essay](https://magazine.sebastianraschka.com/p/beyond-standard-llms), unpacking the four post-transformer architecture families he surveys &mdash; linear-attention hybrids, text diffusion, code world models, small recursive transformers &mdash; with diagrams, code, and an interactive widget per deck. Read alongside the article.

| # | Title | Status | Description |
|---|-------|--------|-------------|
| 06 | [Linear-Attention Hybrids](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_01_Linear_Attention_Hybrids/) | live | MiniMax-M1, Qwen3-Next, DeepSeek V3.2, Kimi Linear &middot; gated DeltaNet maths &middot; the 3:1 hybrid pattern &middot; the MiniMax-M2 reversal &middot; interactive KV-cache calculator. |
| 07 | [Text Diffusion Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_02_Text_Diffusion/) | live | LLaDA, Gemini Diffusion &middot; iterative denoising vs next-token &middot; conditional-dependency limits, no-streaming, tool-use unknowns &middot; interactive diffusion-vs-autoregressive token visualiser. |
| 08 | [Code World Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_03_Code_World_Models/) | live | CWM 32B &middot; world-modelling mid-training &middot; structured execution traces &middot; SWE-bench parity at 4&times; smaller &middot; interactive world-model rollout stepper with bug-injection. |
| 09 | [Small Recursive Transformers](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_04_Small_Recursive_Transformers/) | live | HRM, TRM (7M params, &dollar;500 to train) &middot; ARC-AGI &middot; the attention-not-required ablation &middot; interactive recursive trace viewer on a 4&times;4 puzzle. |
| 10 | [When to Reach for Non-Transformer](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_05_Decision_Tree/) | live | Synthesis. Cost-vs-capability frontier &middot; why standard transformers are still the default &middot; composition (specialist as tool) &middot; interactive decision-tree walker for your own workload. |

## Where this fits

Part of the [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs) &mdash; an index of presentation series for AI/LLM engineers.
