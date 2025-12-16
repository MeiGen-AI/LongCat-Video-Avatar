# Longcat-Video-Avatar
* 🔥 Dec 16, 2025: 🚀 We are excited to announce the release of LongCat-Video-Avatar, a unified model that delivers expressive and highly dynamic audio-driven character animation, supporting native tasks including Audio-Text-to-Video, Audio-Text-Image-to-Video, and Video Continuation with seamless compatibility for both single-stream and multi-stream audio inputs. The release includes our Technical Report, [code](https://github.com/meituan-longcat/LongCat-Video), [model weights](https://huggingface.co/meituan-longcat/LongCat-Video-Avatar), and [project page](https://github.com/MeiGen-AI/LongCat-Video-Avatar).

## ✨ Key Features: 
- **Support Multiple Generation Modes**: one unified model can be used for audio-text-to-video (AT2V) generation,  audio-text-image-to-video （ATI2V） generation， and Video Continuation.
- **Natural Human Dynamics**: The disentangled unconditional guidance is designed to effectively decouple speech signals from motion dynamics for natural behavior.
- **Avoid Repetitive Content**: The reference skip attention is adopted to​ strategically incorporates reference cues to preserve identity while preventing excessive conditional image leakage
- **Alleviate Error Accumulation from VAE**: Cross-Chunk Latent Stitching is designed to eliminates redundant VAE decode-encode cycles to reduce pixel degradation in long sequences


