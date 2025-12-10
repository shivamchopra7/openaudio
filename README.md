<div align="center">

# 🎵 OpenAudio 🎵
### *The Symphony of Speech Synthesis*

[![Discord](https://img.shields.io/discord/1214047546020728892?color=%23738ADB&label=Discord&logo=discord&logoColor=white&style=flat-square)](https://discord.gg/Es5qTB9BcN)
[![Docker](https://img.shields.io/docker/pulls/fishaudio/fish-speech?style=flat-square&logo=docker)](https://hub.docker.com/r/fishaudio/fish-speech)
[![HuggingFace](https://img.shields.io/badge/🤗%20-space%20demo-yellow)](https://huggingface.co/spaces/fishaudio/fish-speech-1)

</div>

---

## 🎼 The Overture

**OpenAudio** (formerly Fish Speech) is a revolutionary text-to-speech orchestration, blending advanced voice cloning with multilingual support. Like a world-class conductor, it turns your text into a majestic audio performance.

Whether you need a whisper, a shout, or a heartfelt monologue, OpenAudio hits every note with precision.

## 🎻 The Ensemble (Features)

*   **🌍 World Tour Ready**: Fluent in English, Japanese, Korean, Chinese, French, German, Arabic, and Spanish.
*   **🎭 Full Emotional Range**: Control the mood with tags like `(sad)`, `(excited)`, `(whispering)`, or even `(laughing)`.
*   **👯‍♂️ Zero-Shot Voice Cloning**: Just 10-30 seconds of reference audio allows the model to mimic any voice.
*   **⚡ Virtuoso Speed**: Blazing fast inference, optimized for GPUs.
*   **🧠 Two Maestros**:
    *   **S1 (4B params)**: The flagship virtuoso for full-featured performance.
    *   **S1-mini (0.5B params)**: The agile soloist, perfect for lighter setups.

## 🎸 Tuning Up (Installation)

Getting the band together is simple with our automated scripts.

1.  **Download** this repository.
2.  **Run** the installer script:
    *   **Windows**: Double-click `install.js` (if using Pinokio or formatted environment) or setting up the environment manually.
    *   *(Note: This codebase is optimized for Pinokio one-click installers).*

## 🎤 Taking the Stage (Usage)

Once your instruments are tuned, it's time to play.

1.  **Start the Engine**: Run `start.js` to boot up the backend.
2.  **Open the WebUI**: Conduct the orchestra from your browser.
3.  **Input Lyrics**: Type your text, add emotional directions like `(excited)`, and press generate.
4.  **Enjoy the Music**: Listen to the lifelike output.

## 🎹 The Sheet Music (Technical Specs)

| Model | WER | CER | Meaning |
| :--- | :--- | :--- | :--- |
| **S1** | **0.008** | **0.004** | Pitch perfect accuracy |
| **S1-mini** | **0.011** | **0.005** | Incredible efficiency |

> [!TIP]
> **Pro Tip**: Use the "Reference Audio" feature to clone voices with uncanny accuracy. It's like having the original artist in the booth!

## 👏 Encore & Credits

Standing ovation to the open-source community and the giants whose shoulders we stand on:
*   VITS2, Bert-VITS2, GPT VITS, and the entire research community.
*   Our amazing contributors and users.

---

<div align="center">
<i>"Music is the shorthand of emotion." - Leo Tolstoy (and OpenAudio)</i> 🎶
</div>
