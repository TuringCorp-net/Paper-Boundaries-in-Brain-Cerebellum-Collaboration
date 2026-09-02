# Models and Environment

| Model | Role | Size | Runtime | Notes |
|---|---|---|---|---|
| DeepSeek v4-flash | cloud brain / cerebellum | 284B total / 13B active | DeepSeek API | baseline and cheap executor |
| DeepSeek v4-pro | cloud brain (scenario) | 1.6T total / 49B active | DeepSeek API | high-priced brain scenario |
| Gemma 4 e4B (gemma4:e4b-mlx) | local cerebellum | 14B parameters, ~10GB MLX | Mac M1 Pro, MLX | main local executor |
| Qwen3.5 4B | local cerebellum | ~5GB | Mac (Ollama/MLX) | mid-tier local model |
| Qwen3.5 0.8B | local cerebellum | ~1GB | Mac (Ollama/MLX) | small-tier local model |

Agent framework: DSH (DeepSeek Harness); G-series runs use orchestration, tool, or sub-agent forms with independent sessions.
Reasoning toggle: think:false / think:true (Gemma); reasoning_effort settings per provider.
