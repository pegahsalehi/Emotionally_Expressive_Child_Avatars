# Emotionally_Expressive_Child_Avatars

[![View on arXiv](https://img.shields.io/badge/arXiv-2506.13477-red)](https://arxiv.org/abs/2506.13477)

[![Watch the video](https://img.youtube.com/vi/c1kzG0QLAeQ/0.jpg)](https://youtu.be/c1kzG0QLAeQ)




![Diagram](assets/dev-pipeline.png)
![Diagram](assets/arch.png)
rchitecture for real-time emotionally expressive child avatars. PC1 processes speech input (Google Cloud
STT), generates a text response via a large language model (LLM), and synthesizes speech using Amazon Polly TTS.
The resulting audio is analyzed by NVIDIA Audio2Face to extract emotional parameters for facial animation. PC2
renders a customizable Metahuman avatar (Unreal Engine) driven by this emotional data in real time. Synchronization
is achieved using the Live Link plugin, and the system supports deployment in both desktop and VR environments.
