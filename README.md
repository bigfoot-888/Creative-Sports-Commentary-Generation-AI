# Creative Sports Video Commentary with AI

This project generates creative sports-style commentary for any type of video using a combination of computer vision techniques, and large language models. The system detects objects in the video, tracks their movements, and generates audio commentary using either Llama-3.2-1B-Instruct or GPT-Neo-125M. It then combines both outputs, the generated audio and the annotated video, for the final result.

---

## Features

- Object detection using YOLOv5
- Movement tracking and interaction detection
- Text commentary generation using Llama-3.2-1B-Instruct or GPT-Neo-125M
- Audio generation using gTTS
- Video output with synchronized commentary
- Works in Google Colab for easy setup

---

## Requirements

### Python packages

Install all required packages with:

```bash
pip install -r requirements.txt
