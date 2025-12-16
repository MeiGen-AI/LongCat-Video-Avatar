# LongCat-Video-Avatar 

<div align="center">
  <img src="assets/icons/longcat-video-avatar_logo.svg" width="45%" alt="LongCat-Video-Avatar" />
</div>
<hr>

<div align="center" style="line-height: 1;">
  <a href='https://meituan-longcat.github.io/LongCat-Video/'><img src='https://img.shields.io/badge/Project-Page-green'></a>
  <a href='https://github.com/meituan-longcat/LongCat-Video/blob/main/assets/LongCat-Video-Avatar-Tech-Report.pdf'><img src='https://img.shields.io/badge/Technique-Report-red'></a>
  <a href='https://huggingface.co/meituan-longcat/LongCat-Video-Avatar'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Model-blue'></a>
</div>

<div align="center" style="line-height: 1;">
  <a href='https://github.com/meituan-longcat/LongCat-Flash-Chat/blob/main/figures/wechat_official_accounts.png'><img src='https://img.shields.io/badge/WeChat-LongCat-brightgreen?logo=wechat&logoColor=white'></a>  
  <a href='https://x.com/Meituan_LongCat'><img src='https://img.shields.io/badge/Twitter-LongCat-white?logo=x&logoColor=white'></a>
</div>

<div align="center" style="line-height: 1;">
  <a href='LICENSE'><img src='https://img.shields.io/badge/License-MIT-f5de53?&color=f5de53'></a>
</div>


## 🔥 Latest News
* Dec 16, 2025: 🚀 We are excited to announce the release of **[LongCat-Video-Avatar](https://github.com/MeiGen-AI/LongCat-Video-Avatar)**, a unified model that delivers expressive and highly dynamic audio-driven character animation, supporting native tasks including Audio-Text-to-Video, Audio-Text-Image-to-Video, and Video Continuation with seamless compatibility for both single-stream and multi-stream audio inputs. The release includes our Technical Report, [code](https://github.com/meituan-longcat/LongCat-Video), [model weights](https://huggingface.co/meituan-longcat/LongCat-Video-Avatar), and [project page](https://github.com/MeiGen-AI/LongCat-Video-Avatar).

## ✨ Key Features: 
- **Support Multiple Generation Modes**: one unified model can be used for audio-text-to-video (AT2V) generation,  audio-text-image-to-video （ATI2V） generation， and Video Continuation.
- **Natural Human Dynamics**: The disentangled unconditional guidance is designed to effectively decouple speech signals from motion dynamics for natural behavior.
- **Avoid Repetitive Content**: The reference skip attention is adopted to​ strategically incorporates reference cues to preserve identity while preventing excessive conditional image leakage
- **Alleviate Error Accumulation from VAE**: Cross-Chunk Latent Stitching is designed to eliminates redundant VAE decode-encode cycles to reduce pixel degradation in long sequences


