### Hi ! Here is Coobiw 👋

#### 🙋‍♂️ About Me:

- 👨‍🦰 I’m currently a M.Phil candidate of Peking University. <img src="https://www.pku.edu.cn/pku_logo_red.png" width = "50" height = "40"  align=center />
- ❤️‍🔥 Now, I am intersted in Multi-modal Learning especially MLLM.
- 💥 In 2023 summer, I take part in [OSPP(Open Source Promotion Plan)](https://summer-ospp.ac.cn/) Summer Camp <img src="https://summer-ospp.ac.cn/vite.svg" width = "60" height = "35"  align=center />, with the honor of contributing for [MMPretrain](https://github.com/open-mmlab/mmpretrain) to build prompt-based classifier. <img src="https://oss.openmmlab.com/www/community/mm.png" width = "60" height = "35"  align=center />
   - Now, the implement of zero-shot CLIP classifier has been merged to the main branch. [PR Link](https://github.com/open-mmlab/mmpretrain/pull/1737)
   - The implement of RAM(Recognize Anything Model) has been merged to the dev branch. Welcome to use the gradio WebUI to test it on MMPretrain! [PR Link](https://github.com/open-mmlab/mmpretrain/pull/1802)
- 💥 2023.10: I implement MiniGPT4Qwen, which is a toy model aligning MiniGPT4 with Qwen-Chat LLM model. I just use 18.8k high quality instruction-tuning data(bi-lingual, selected from minigpt4 and llava). Just fine-tuning the projection layer (3M trainable parameters), this model support Chinese and English! [MiniGPT4Qwen](https://github.com/Coobiw/MiniGPT4Qwen)
- 💥 2024.2:  I extend MiniGPT4Qwen to MPP-Qwen14B(Multimodal Pipeline Parallel), scaling up both the LLM(to Qwen-14B-Chat) and pretrain-data(using LLaVA-pretrain-data). I also unfreeze the whole LLM during SFT-stage. **All training is conducted on 3090/4090 GPUs.** To prevent poverty (24GB of VRAM) from limiting imagination, I implemented an MLLM version based on deepspeed Pipeline Parallel. Pre-training can be completed in 22 hours on 2x4090s, while SFT requires training on 6x4090s (because it needs to fully activate the LLM), but due to the small amount of data, it only takes several hours.[MPP-Qwen14B](https://github.com/Coobiw/MiniGPT4Qwen)
<br />
<br />

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Coobiw&show_icons=true&theme=rose)
