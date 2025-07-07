# Emotionally_Expressive_Child_Avatars

[![View on arXiv](https://img.shields.io/badge/arXiv-2506.13477-red)](https://arxiv.org/abs/2506.13477)


![Diagram](assets/dev-pipeline.png)
![Diagram](assets/arch.png)
rchitecture for real-time emotionally expressive child avatars. PC1 processes speech input (Google Cloud
STT), generates a text response via a large language model (LLM), and synthesizes speech using Amazon Polly TTS.
The resulting audio is analyzed by NVIDIA Audio2Face to extract emotional parameters for facial animation. PC2
renders a customizable Metahuman avatar (Unreal Engine) driven by this emotional data in real time. Synchronization
is achieved using the Live Link plugin, and the system supports deployment in both desktop and VR environments.


<div align="center">
<table>
  <tr>
    <td>
      <a href="https://youtu.be/c1kzG0QLAeQ">
        <img src="https://img.youtube.com/vi/c1kzG0QLAeQ/0.jpg" alt="bn" width="200"/>
      </a><br/><center><b>Sad</b></center>
    </td>
    <td>
      <a href="https://youtu.be/rLX_293HqQA">
        <img src="https://img.youtube.com/vi/rLX_293HqQA/0.jpg" alt="bsh" width="200"/>
      </a><br/><center><b>Joy</b></center>
    </td>
    <td>
      <a href="https://youtu.be/yDPRW7z9vgA">
        <img src="https://img.youtube.com/vi/yDPRW7z9vgA/0.jpg" alt="ba" width="200"/>
      </a><br/><center><b>Angry</b></center>
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://youtu.be/m37s2LGMxEY">
        <img src="https://img.youtube.com/vi/m37s2LGMxEY/0.jpg" alt="gn" width="200"/>
      </a><br/><center><b>Sad</b></center>
    </td>
    <td>
      <a href="https://youtu.be/jgnOVcH5GnE">
        <img src="https://img.youtube.com/vi/jgnOVcH5GnE/0.jpg" alt="gsh" width="200"/>
      </a><br/><center><b>Joy</b></center>
    </td>
    <td>
      <a href="https://youtu.be/z71hsrbcL_I">
        <img src="https://img.youtube.com/vi/z71hsrbcL_I/0.jpg" alt="ga" width="200"/>
      </a><br/><center><b>Angry</b></center>
    </td>
  </tr>
</table>

