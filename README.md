---
license: apache-2.0
tags:
- code
- safetensors
- chatbot
- 0.7B
- fill-mask
datasets:
- Keynote-Technology/PLANE-2K
- togethercomputer/RedPajama-Data-V2
---

# TinyKAI 0.7B
![image/png](https://cdn-uploads.huggingface.co/production/uploads/6500c7c912c1442d994c36e5/kzoTQKbdAXNfOxw5hUts3.png)

## Model Details
TinyKAI-0.7B is one of the world's SMALLEST "large" language models EVER!
We acheived such a feat by essentially compressing [GPT2](https://huggingface.co/gpt2) and squeezing it to fit into one sub-GB pytorch.bin file!

## Uses
Due to being one of the tiniest "large" language models on huggingface, many corners had to be cut. TinyKAI-0.7B has a max output of only 150 characters per computation (without repeating itself). Therefore, TinyKAI is only intended for research purposes.
<!-- Address questions around how the model is intended to be used, including the foreseeable users of the model and those affected by the model. -->

## Banned Use
TinyKAI-1B is governed by the [apache 2.0 liscense](https://choosealicense.com/licenses/apache-2.0/), and therefore means that whatever the license deems unacceptable shall not be allowed. We specificaly ban the use of  [ANY AND ALL KAI MODELS](https://huggingface.co/collections/Keynote-Technology/kai-large-language-models) for hate speech and academic dishonesty due to [legal](https://www.ftc.gov/news-events/news/press-releases/2022/06/ftc-report-warns-about-using-artificial-intelligence-combat-online-problems) and ethical issues.

## Limitations
2 thousand characters max output length (including spaces and repeating text), English only, and extremely tiny (1GB).

## Recommendations
TinyKAI-0.7B is a very small model, and is good for AI research especially.
