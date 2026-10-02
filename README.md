# Qwen 3.8 27B Uncensored Chat

**Qwen 3.8 27B Uncensored Chat** is a local desktop client for Alibaba's dense 27B, not Max. qwen ai / qwen chat / chat qwen through ollama qwen, llama.cpp or LM Studio. No qwen api key. FAQ covers qwen 3.8 27b download, qwen 3.8 27b requirements, qwen 3.8 ollama and the obliterated GGUF.

<img width="200" height="200" alt="images1" src="https://github.com/user-attachments/assets/279a8626-3760-45df-b84d-75471742f5f7" /><img width="200" height="200" alt="images2" src="https://github.com/user-attachments/assets/f2a2953f-03ef-4f8b-bc17-6cc59de7bc6a" />
<img width="1630" height="965" alt="images3" src="https://github.com/user-attachments/assets/77acb704-872a-483f-a06b-79c1763854f7" />

## What's new in v3.8.28 (August 26, 2026)
- Q4_K_M loader less RAM on 16 GB cards
- Ollama qwen 3.8 reconnect
- Qwen coder preset
- Hugging Face pull helper
<img width="318" height="159" alt="images4" src="https://github.com/user-attachments/assets/adca7f7c-0ce5-4824-8950-d02d23228391" />
<img width="640" height="637" alt="images5" src="https://github.com/user-attachments/assets/49c24b99-b9d1-422a-9170-5e47ac474422" />
<img width="310" height="163" alt="images6" src="https://github.com/user-attachments/assets/43c13190-c6de-4ab3-8269-1a5987b523bb" />

## Key Features
- qwen 3.8 / qwen3.8 dense 27B
- Uncensored / obliterated GGUF option
- Ollama, llama.cpp, LM Studio, Hugging Face
- Streaming qwen chat UI
- qwen code / qwen coder presets
- After the first download, fully local

<img width="3418" height="1926" alt="images7" src="https://github.com/user-attachments/assets/81a74129-405b-4c08-956d-cfe37ec07e3d" />
<img width="723" height="423" alt="images10" src="https://github.com/user-attachments/assets/1755c612-ddaf-4ff9-a98e-7b853820f03b" />

## Getting Started
1. Get v3.8.28.
2. Run `Qwen38Uncensored.exe`.
3. Pull weights (`ollama pull qwen3.8:27b` or GGUF).
4. Pick Ollama or llama.cpp in Settings.

```
ollama pull qwen3.8:27b
huggingface-cli download bartowski/Qwen3.8-27B-GGUF --include "*Q4_K_M*" --local-dir ./models
```

<img width="1200" height="632" alt="images8" src="https://github.com/user-attachments/assets/672bba42-fc72-4bb8-91d8-448df8e9b20e" />
<img width="3424" height="1768" alt="images9" src="https://github.com/user-attachments/assets/3e5baade-3578-498a-972a-b6a083268866" />

## FAQ

**27B vs qwen 3.8 max?**
27B is the dense local size. Max is the huge MoE. This app is the 27B uncensored chat client.

**Requirements?**
Q4_K_M ~18 GB RAM or 16 GB VRAM. Q8 ~32 GB. RTX 3090 class is comfortable.

**Alibaba qwen license?**
Apache-style weights, MIT app.

## Requirements
Windows 10/11, macOS 12+ or Linux · 18 GB RAM (Q4) · NVIDIA 16 GB VRAM recommended

## License
<img width="739" height="415" alt="images11" src="https://github.com/user-attachments/assets/b16a0f84-057d-4295-8c42-b8df8d6de103" />
