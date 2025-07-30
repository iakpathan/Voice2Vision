# Voice2Vision – AI Art Generator with Enhanced Prompts & Styles

> **An intelligent, user-friendly platform for generating stunning AI images from voice or text prompts, powered by Groq + Stable Diffusion XL.**

---

## Problem Statement

Creating high-quality, stylistically consistent visuals remains **costly, slow, and skill-dependent** for many users — especially across design, education, marketing, and content industries. There’s a growing need for tools that make visual content creation **fast, accessible, and style-rich** without sacrificing quality.

---

## Solution

This project offers a streamlined AI-powered **image generation platform** that:
- Accepts **voice-based natural language input**
- Enhances prompts using **LLMs like Groq’s LLaMA 3**
- Generates high-resolution images with **Stable Diffusion XL**
- Provides **style selection**, **downloadable output**, and **memory-efficient execution**

By blending state-of-the-art **LLMs** and **open-source diffusion models**, users can create compelling, personalized visuals without deep technical or artistic expertise.

---

## ✨ Features

-  **Voice Input**  
  Record voice in-browser to generate descriptive prompts

-  **Prompt Enhancement with LLM (Groq LLaMA 3)**  
  Automatically enhance user prompts using rich artistic language

-  **Custom Art Styles**  
  Choose from styles like *Realistic, Anime, Van Gogh, Cyberpunk*, and more

- **AI Image Generation**  
  Powered by **Stable Diffusion XL**, ensuring high-quality, stylized results

- **Downloadable Output**  
  Save generated images locally for reuse or publishing

---

##  Significance of AI Image Generation

- Enhances creativity and idea visualization  
- Saves time and reduces design/photography costs  
- Scales content creation for marketing and media  
- Enables mass personalization of visuals  
- Supports innovation in healthcare, education, and architecture  
- Makes visual creation accessible to non-designers  
- Provides synthetic data for AI/ML training  
- Simulates rare or complex scenarios  
- Improves communication and storytelling  
- Accelerates prototyping and design workflows

---

##  Tech Stack

| Component        | Technology                             |
|------------------|----------------------------------------|
| LLM Integration  | Groq API with LLaMA 3                  |
| Voice Recording  | JavaScript (browser-side, Colab JS)    |
| Audio Handling   | `pydub`, `faster-whisper`              |
| Prompt Handling  | Python + Transformers (token trimming) |
| Image Generation | `diffusers`, `StableDiffusionXL`       |
| UI / Notebook    | Google Colab (with ipywidgets)         |

---

##  How to Run (in Google Colab)

1. Open the Colab notebook
2. Run the first cell to install dependencies
3. Record voice or type prompt
4. Select style
5. Let LLM enhance your prompt
6. Generate image
7. Download your artwork!

---

##  License

This project is open-source and intended for educational and non-commercial use. Refer to the individual model licenses for reuse rights.

---

##  Acknowledgements

- [Groq API](https://groq.com/)
- [Hugging Face – Stable Diffusion XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)
- [faster-whisper](https://github.com/guillaumekln/faster-whisper)
- [Diffusers by Hugging Face](https://github.com/huggingface/diffusers)

---

> Made with idea by combining voice, vision, and generative AI.
