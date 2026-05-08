---
supportedModelGroups:
  - id: llm
    title: LLM
    intro: Mainstream open LLM families with public support status across hardware classes.
    items:
      - name: DeepSeek-V3/R1/V3.1
        support: [NPU, MLU]
      - name: DeepSeek-V3.2
        support: [NPU, MLU]
      - name: DeepSeek-R1-Distill-Qwen
        support: [NPU]
      - name: Qwen2/2.5/QwQ
        support: [NPU, MLU, ILU]
      - name: Qwen3
        support: [NPU, MLU, ILU]
      - name: Qwen3 MoE
        support: [NPU, MLU, ILU]
      - name: Kimi-k2
        support: [NPU]
      - name: Llama2/3
        support: [NPU, ILU]
      - name: GLM 4.5 / 4.6 / 4.7 / 5
        support: [NPU]
  - id: vlm
    title: VLM
    intro: Vision-language model support exposed in the public documentation.
    items:
      - name: MiniCPM-V
        support: [NPU]
      - name: MiMo-VL
        support: [NPU]
      - name: Qwen2.5-VL
        support: [NPU, MLU]
      - name: Qwen3-VL
        support: [NPU, MLU]
      - name: Qwen3-VL-MoE
        support: [NPU, MLU]
      - name: GLM-4.6V
        support: [NPU]
      - name: VLM-R1
        support: [NPU]
  - id: dit
    title: DiT
    intro: Diffusion transformer workload support.
    items:
      - name: Flux
        support: [NPU]
  - id: rec
    title: Rec
    intro: Recommendation workload support.
    items:
      - name: OneRec
        support: [NPU]
      - name: Qwen2 (Rec)
        support: [NPU]
      - name: Qwen2.5 (Rec)
        support: [NPU]
      - name: Qwen3 (Rec)
        support: [NPU]
  - id: rerank
    title: Rerank
    intro: Reranking workload support.
    items:
      - name: Qwen3-Reranker
        support: [NPU]
---

Supported model data consumed by `src/pages/supported-models.astro`.
