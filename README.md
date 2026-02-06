# Creative Sports Video Commentary with AI

This project generates creative sports-style commentary for any type of video using a combination of computer vision techniques and large language models. The system detects objects in the video, tracks their movements, and generates audio commentary using either Llama-3.2-1B-Instruct or GPT-Neo-125M. It then combines the generated audio and the annotated video for the final result.

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

- **LLaMa model:** To use Llama-3.2-1B-Instruct, you need a Hugging Face account and token.  
  - If access is denied, request permission here: [Meta-LLaMA](https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct).  
  - Instructions are also included inside the notebook.
- **RAM:** For smooth execution, ensure your system or Colab session has at least 12 GB of RAM.
- **FFmpeg:** Needed to combine the final audio and video.  
  - For local installations, download it here: [FFmpeg Downloads](https://www.ffmpeg.org/download.html)
- **Python packages:** Install all required packages locally with:

```bash
pip install -r requirements.txt

