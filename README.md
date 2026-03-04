# Awesome-VLA-Papers

This repository contains the list of representative VLA works in the survey “[*A Survey on Vision-Language-Action Models: An Action Tokenization Perspective*](https://arxiv.org/abs/2507.01925)”, along with relevant reference materials.

# Foundation Models

## Language Foundation Models

- **Transformer**, *Attention is All You Need*, 2017.06, NIPS 2017. [[📄 Paper](https://arxiv.org/abs/1706.03762)]
- **USE**, *Universal sentence encoder*, 2018.03. [[📄 Paper](https://arxiv.org/abs/1803.11175)]
- **GPT-1**, *Improving language understanding by generative pre-training*, 2018.06. [[📄 Paper](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)]
- **BERT**, *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*, 2018.10, NAACL 2019. [[📄 Paper](https://arxiv.org/abs/1810.04805)] [[💻 Code](https://github.com/google-research/bert)] [[🤗 Model](https://huggingface.co/google-bert)]
- **GPT-2**, *Language Models are Unsupervised Multitask Learners*, 2019.02. [[📄 Paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)] [[💻 Code](https://github.com/openai/gpt-2)]
- **MUSE**, *Multilingual universal sentence encoder for semantic retrieval*, 2019.07. [[📄 Paper](https://arxiv.org/abs/1907.04307)] [[💻 Code](https://github.com/facebookresearch/MUSE)]
- **T5**, *Exploring the limits of transfer learning with a unified text-to-text transformer*, 2019.10, JMLR 2020. [[📄 Paper](https://www.jmlr.org/papers/volume21/20-074/20-074.pdf)] [[💻 Code](https://github.com/google-research/text-to-text-transfer-transformer)] [[🤗 Model](https://huggingface.co/google-t5)]
- **GPT-3**, *Language Models are Few-Shot Learners*, 2020.05, NeurIPS 2020. [[📄 Paper](https://arxiv.org/abs/2005.14165)]
- **InstructGPT**, *Training language models to follow instructions with human feedback*, 2022.03, NeurIPS 2022. [[📄 Paper](https://arxiv.org/abs/2203.02155)] [[🌍 Website](https://openai.com/index/instruction-following/)]
- **Chinchilla**, *Training Compute-Optimal Large Language Models*, 2022.03, NeurIPS 2022. [[📄 Paper](https://arxiv.org/abs/2203.15556)]
- **ChatGPT**, 2022.11. [[🌍 Website](https://openai.com/index/chatgpt/?utm_source=chatgpt.com)]
- **LLaMA**, *LLaMA: Open and Efficient Foundation Language Models*, 2023.02. [[📄 Paper](https://arxiv.org/abs/2302.13971)] [[💻 Code](https://github.com/meta-llama/llama)] [[🤗 Model](https://huggingface.co/meta-llama)]
- **GPT-4**, 2023.03. [[📄 Paper](https://arxiv.org/abs/2303.08774)] [[🌍 Website](https://openai.com/index/gpt-4-research/)]
- **Claude**, 2023.03. [[🌍 Website](https://www.anthropic.com/news/introducing-claude)]
- **Llama 2**, *Llama 2: Open Foundation and Fine-Tuned Chat Models*, 2023.07. [[📄 Paper](https://arxiv.org/abs/2307.09288)] [[🤗 Model](https://huggingface.co/meta-llama)]
- **Claude 2**, 2023.07. [[🌍 Website](https://www.anthropic.com/news/claude-2)]
- **Mistral**, *Mistral 7B*, 2023.10. [[📄 Paper](https://arxiv.org/abs/2310.06825)] [[🤗 Model](https://huggingface.co/mistralai)]
- **Mamba**, *Mamba: Linear-Time Sequence Modeling with Selective State Spaces*, 2023.12, COML. [[📄 Paper](https://arxiv.org/abs/2312.00752)] [[💻 Code](https://github.com/state-spaces/mamba)]
- **Mixtral**, *Mixtral of Experts*, 2024.01. [[📄 Paper](https://arxiv.org/abs/2401.04088)] [[🤗 Model](https://huggingface.co/mistralai)]
- **Gemma**, *Gemma: Open Models Based on Gemini Research and Technology*, 2024.03. [[📄 Paper](https://arxiv.org/abs/2403.08295)] [[🌍 Website](https://deepmind.google/models/gemma/)]
- **Claude 3**, 2024.03. [[🌍 Website](https://www.anthropic.com/news/claude-3-family)]
- **Llama 3**, *The Llama 3 Herd of Models*, 2024.07. [[📄 Paper](https://arxiv.org/abs/2407.21783)] [[🌍 Website](https://www.llama.com/models/llama-3/)] [[🤗 Model](https://huggingface.co/meta-llama)]
- **Gemma 2**, *Gemma 2: Improving Open Language Models at a Practical Size*, 2024.08. [[📄 Paper](https://arxiv.org/abs/2408.00118)] [[🤗 Model](https://huggingface.co/google/gemma-2-2b-it)]
- **OpenAI o1**, 2024.12. [[🌍 Website](https://openai.com/o1/)]
- **Gemini 2.0 Flash**, 2025.01. [[🌍 Website](https://blog.google/technology/google-deepmind/google-gemini-ai-update-december-2024/)]
- **DeepSeek-R1**, *DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning*, 2025.01. [[📄 Paper](https://arxiv.org/abs/2501.12948)] [[🤗 Model](https://huggingface.co/deepseek-ai/DeepSeek-R1)]
- **Gemini 2.0 Pro**, 2025.02. [[🌍 Website](https://blog.google/technology/google-deepmind/gemini-model-updates-february-2025/)]
- **Gemini 2.5 Pro**, 2025.03. [[🌍 Website](https://deepmind.google/models/gemini/pro/)]
- **Gemma 3**, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.19786)] [[🌍 Website](https://deepmind.google/models/gemma/gemma-3/)]
- **Gemini 2.5 Flash**, 2025.04. [[🌍 Website](https://deepmind.google/models/gemini/flash/)]
- **Claude 4**, 2024.05. [[🌍 Website](https://www.anthropic.com/news/claude-4)]

## Vision Foundation Models

- **ViT**, *An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale*, 2020.10, ICLR 2021. [[📄 Paper](https://arxiv.org/abs/2010.11929)] [[💻 Code](https://github.com/google-research/vision_transformer)]
- **CLIP**, *Learning Transferable Visual Models From Natural Language Supervision*, 2021.02, ICML 2021. [[📄 Paper](https://arxiv.org/abs/2103.00020)] [[💻 Code](https://github.com/OpenAI/CLIP)]
- **DINO**, *Emerging Properties in Self-Supervised Vision Transformers*, 2021.04, ICCV 2021. [[📄 Paper](https://arxiv.org/abs/2104.14294)] [[💻 Code](https://github.com/facebookresearch/dino)]
- **GLIP**, *Grounded Language-Image Pre-training*, 2021.12, CVPR 2022. [[📄 Paper](https://arxiv.org/abs/2112.03857)] [[💻 Code](https://github.com/microsoft/GLIP)]
- **GLIDE**, *GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models*, 2021.12, ICML 2022. [[📄 Paper](https://arxiv.org/abs/2112.10741)] [[💻 Code](https://github.com/openai/glide-text2im)]
- **Stable Diffusion**, *High-Resolution Image Synthesis with Latent Diffusion Models*, 2021.12, CVPR 2022. [[📄 Paper](https://arxiv.org/abs/2112.10752)] [[💻 Code](https://github.com/CompVis/latent-diffusion)]
- **DALL-E 2**, *Hierarchical Text-Conditional Image Generation with CLIP Latents*, 2022.04, CVPR 2022. [[📄 Paper](https://arxiv.org/abs/2204.06125)] [[🌍 Website](https://openai.com/index/dall-e-2/)]
- **Imagen**, *Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding*, 2022.05, NeurIPS 2022. [[📄 Paper](https://arxiv.org/abs/2205.11487)] [[🌍 Website](https://imagen.research.google/)]
- **Stable Diffusion 2**, 2022.11. [[🌍 Website](https://github.com/Stability-AI/StableDiffusion)]
- **ControlNet**, *Adding Conditional Control to Text-to-Image Diffusion Models*, 2023.02, ICCV 2023. [[📄 Paper](https://arxiv.org/abs/2302.05543)] [[💻 Code](https://github.com/lllyasviel/ControlNet)]
- **PVDM**, *Video Probabilistic Diffusion Models in Projected Latent Space*, 2023.02, CVPR 2023. [[📄 Paper](https://arxiv.org/abs/2302.07685)] [[🌍 Website](https://sihyun.me/PVDM/)] [[💻 Code](https://github.com/sihyun-yu/PVDM)]
- **SigLIP**, *Sigmoid Loss for Language Image Pre-Training*, 2023.03, ICCV 2023. [[📄 Paper](https://arxiv.org/abs/2303.15343)] [[💻 Code](https://github.com/google-research/big_vision)]
- **Grounding DINO**, *Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection*, 2023.03, ECCV 2024. [[📄 Paper](https://arxiv.org/abs/2303.05499)] [[💻 Code](https://github.com/IDEA-Research/GroundingDINO)]
- **DINOv2**, *DINOv2: Learning Robust Visual Features without Supervision*, 2023.04, TMLR 2024. [[📄 Paper](https://arxiv.org/abs/2304.07193)] [[🌍 Website](https://ai.meta.com/blog/dino-v2-computer-vision-self-supervised-learning/)] [[💻 Code](https://github.com/facebookresearch/dinov2)]
- **SAM**, *Segment Anything*, 2023.04, ICCV 2023. [[📄 Paper](https://arxiv.org/abs/2304.02643)] [[🌍 Website](https://segment-anything.com/)] [[💻 Code](https://github.com/facebookresearch/segment-anything)] [[📊 Dataset](https://segment-anything.com/dataset/index.html)]
- **CoTracker**, *CoTracker: It is Better to Track Together*, 2023.07, ECCV 2024. [[📄 Paper](https://arxiv.org/abs/2307.07635)] [[🌍 Website](https://co-tracker.github.io/)] [[💻 Code](https://github.com/facebookresearch/co-tracker)]
- **Cutie**, *Putting the Object Back into Video Object Segmentation*, 2023.10, CVPR 2024 Highlight. [[📄 Paper](https://arxiv.org/abs/2310.12982)] [[🌍 Website](https://hkchengrex.com/Cutie/)] [[💻 Code](https://github.com/hkchengrex/Cutie)]
- **VideoCrafter1**, *VideoCrafter1: Open Diffusion Models for High-Quality Video Generation*, 2023.10. [[📄 Paper](https://arxiv.org/abs/2310.19512)] [[🌍 Website](https://ailab-cvc.github.io/videocrafter1/)] [[💻 Code](https://github.com/AILab-CVC/VideoCrafter)]
- **FoundationPose**, *FoundationPose: Unified 6D Pose Estimation and Tracking of Novel Objects*, 2023.12, CVPR 2024 Highlight. [[📄 Paper](https://arxiv.org/abs/2312.08344)] [[🌍 Website](https://nvlabs.github.io/FoundationPose/)] [[💻 Code](https://github.com/NVlabs/FoundationPose)]
- **HaMeR**, *Reconstructing Hands in 3D with Transformers*, 2023.12, CVPR 2024. [[📄 Paper](https://arxiv.org/abs/2312.05251)] [[🌍 Website](https://geopavlakos.github.io/hamer/)] [[💻 Code](https://github.com/geopavlakos/hamer)] [[📊 Dataset](https://github.com/ddshan/hint)]
- **Depth Anything**, *Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data*, 2024.01, CVPR 2024. [[📄 Paper](https://arxiv.org/abs/2401.10891)] [[🌍 Website](https://depth-anything.github.io/)] [[💻 Code](https://github.com/LiheYoung/Depth-Anything)]
- **Grounded SAM**, *Grounded SAM: Assembling Open-World Models for Diverse Visual Tasks*, 2024.01. [[📄 Paper](https://arxiv.org/abs/2401.14159)] [[💻 Code](https://github.com/IDEA-Research/Grounded-Segment-Anything)]
- **VideoCrafter2**, *VideoCrafter2: Overcoming Data Limitations for High-Quality Video Diffusion Models*, 2024.01, CVPR 2024. [[📄 Paper](https://arxiv.org/abs/2401.09047)] [[🌍 Website](https://ailab-cvc.github.io/videocrafter2/)] [[💻 Code](https://github.com/AILab-CVC/VideoCrafter)]
- **Sora**, *Video generation models as world simulators*, 2024.02. [[🌍 Website](https://openai.com/index/video-generation-models-as-world-simulators/)]
- **Genie**, *Genie: Generative Interactive Environments*, 2024.02, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2402.15391)] [[🌍 Website](https://sites.google.com/view/genie-2024/home)]
- **Stable Diffusion 3**, *Scaling Rectified Flow Transformers for High-Resolution Image Synthesis*, 2024.03, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2403.03206)] [[🤗 Model](https://huggingface.co/stabilityai/stable-diffusion-3-medium)]
- **Grounding DINO 1.5**, *Grounding DINO 1.5: Advance the "Edge" of Open-Set Object Detection*, 2024.05. [[📄 Paper](https://arxiv.org/abs/2405.10300)] [[💻 Code](https://github.com/IDEA-Research/Grounding-DINO-1.5-API)]
- **Depth Anything V2**, *Depth Anything V2*, 2024.06, NeurIPS 2024. [[📄 Paper](https://arxiv.org/abs/2406.09414)] [[🌍 Website](https://depth-anything-v2.github.io/)] [[💻 Code](https://github.com/DepthAnything/Depth-Anything-V2)]
- **SAM 2**, *SAM 2: Segment Anything in Images and Videos*, 2024.08. [[📄 Paper](https://arxiv.org/abs/2408.00714)] [[🌍 Website](https://ai.meta.com/sam2/)] [[💻 Code](https://github.com/facebookresearch/sam2)]
- **Grounded SAM 2**, *Grounded SAM: Assembling Open-World Models for Diverse Visual Tasks*, 2024.08. [[📄 Paper](https://arxiv.org/abs/2401.14159)] [[💻 Code](https://github.com/IDEA-Research/Grounded-SAM-2)]
- **SAMURAI**, *SAMURAI: Adapting Segment Anything Model for Zero-Shot Visual Tracking with Motion-Aware Memory*, 2024.11. [[📄 Paper](https://arxiv.org/abs/2411.11922)] [[🌍 Website](https://yangchris11.github.io/samurai/)] [[💻 Code](https://github.com/yangchris11/samurai)]
- **Genie 2**, *Genie 2: A large-scale foundation world model*, 2024.11. [[🌍 Website](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/)]
- **Veo 3**, *Veo 3*, 2025.05. [[🌍 Website](https://deepmind.google/models/veo/)]

## Vision Language Models

- **BLIP**, *BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation*, 2022.01, ICML 2022. [[📄 Paper](https://arxiv.org/abs/2201.12086)] [[💻 Code](https://github.com/salesforce/BLIP)] [[🤗 Model](https://huggingface.co/collections/Salesforce/blip-models-65242f40f1491fbf6a9e9472)]
- **Flamingo**, *Flamingo: a Visual Language Model for Few-Shot Learning*, 2022.04, NeurIPS 2022. [[📄 Paper](https://arxiv.org/abs/2204.14198)]
- **BLIP-2**, *BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models*, 2023.01, ICML 2023. [[📄 Paper](https://arxiv.org/abs/2301.12597)] [[🤗 Model](https://huggingface.co/collections/Salesforce/blip2-models-65242f91b4c4b4a32e5cb652)]
- **LLaVA**, *Visual Instruction Tuning*, 2023.04, NeurIPS 2023 Oral. [[📄 Paper](https://arxiv.org/abs/2304.08485)] [[🌍 Website](https://llava-vl.github.io/)] [[💻 Code](https://github.com/haotian-liu/LLaVA)] [[📊 Dataset](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K)]
- **Qwen-VL**, *Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond*, 2023.08. [[📄 Paper](https://arxiv.org/abs/2308.12966)] [[💻 Code](https://github.com/QwenLM/Qwen-VL)] [[🤗 Model](https://huggingface.co/Qwen/Qwen-VL)]
- **LLaVA 1.5**, *Improved Baselines with Visual Instruction Tuning*, 2023.10, CVPR 2024 highlight. [[📄 Paper](https://arxiv.org/abs/2310.03744)] [[🌍 Website](https://llava-vl.github.io/)] [[💻 Code](https://github.com/haotian-liu/LLaVA)] [[🤗 Model](https://github.com/haotian-liu/LLaVA/blob/main/docs/MODEL_ZOO.md)] [[📊 Dataset](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K)]
- **Prismatic**, *Prismatic VLMs: Investigating the Design Space of Visually-Conditioned Language Models*, 2024.02, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2402.07865)] [[💻 Code (training)](https://github.com/TRI-ML/prismatic-vlms)] [[💻 Code (evaluation)](https://github.com/TRI-ML/vlm-evaluation)] [[🤗 Model](https://huggingface.co/TRI-ML/prismatic-vlms)]
- **GPT-4o**, 2024.05. [[📄 Paper](https://arxiv.org/abs/2410.21276)] [[🌍 Website](https://openai.com/index/hello-gpt-4o/)]
- **PaliGemma**, *PaliGemma: A versatile 3B VLM for transfer*, 2024.07. [[📄 Paper](https://arxiv.org/abs/2407.07726)] [[🌍 Website](https://huggingface.co/blog/paligemma)]
- **Qwen2-VL**, *Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution*, 2024.09. [[📄 Paper](https://arxiv.org/abs/2409.12191)] [[🌍 Website](https://qwenlm.github.io/blog/qwen2-vl/)] [[🤗 Model](https://huggingface.co/collections/Qwen/qwen2-vl-66cee7455501d7126940800d)]
- **Qwen2.5-VL**, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.13923)] [[🌍 Website](https://qwenlm.github.io/blog/qwen2.5-vl/)] [[💻 Code](https://github.com/QwenLM/Qwen2.5-VL)] [[🤗 Model](https://huggingface.co/collections/Qwen/qwen25-vl-6795ffac22b334a837c0f9a5)]
- **Gemini 2.5 Pro**, 2025.03. [[🌍 Website](https://deepmind.google/models/gemini/pro/)]
- **Gemini 2.5 Flash**, 2025.04. [[🌍 Website](https://deepmind.google/models/gemini/flash/)]

# Language Description as Action Tokens

## Language Plan

- **Language Planner**, *Language Models as Zero-Shot Planners: Extracting Actionable Knowledge for Embodied Agents*, 2022.01, ICML 2022. [[📄 Paper](https://arxiv.org/abs/2201.07207)] [[🌍 Website](https://wenlong.page/language-planner/)] [[💻 Code](https://github.com/huangwl18/language-planner)]
- **Socratic Models**, *Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language*, 2022.04, ICLR 2023. [[📄 Paper](https://arxiv.org/abs/2204.00598)] [[🌍 Website](https://socraticmodels.github.io/)] [[💻 Code](https://github.com/google-research/google-research/tree/master/socraticmodels)]
- **SayCan**, *Do As I Can, Not As I Say: Grounding Language in Robotic Affordances*, 2022.04. [[📄 Paper](https://arxiv.org/abs/2204.01691)] [[🌍 Website](https://say-can.github.io/)] [[💻 Code](https://github.com/google-research/google-research/tree/master/saycan)]
- **Inner Monologue**, *Inner Monologue: Embodied Reasoning through Planning with Language Models*, 2022.07, CoRL 2022. [[📄 Paper](https://arxiv.org/abs/2207.05608)] [[🌍 Website](https://innermonologue.github.io/)]
- **PaLM-E**, *PaLM-E: An Embodied Multimodal Language Model*, 2023.03, ICML 2023. [[📄 Paper](https://arxiv.org/abs/2303.03378)] [[🌍 Website](https://palm-e.github.io/)]
- **EmbodiedGPT**, *EmbodiedGPT: Vision-Language Pre-Training via Embodied Chain of Thought*, 2023.05, NeurIPS 2023. [[📄 Paper](https://arxiv.org/abs/2305.15021)] [[🌍 Website](https://embodiedgpt.github.io/)] [[💻 Code](https://github.com/EmbodiedGPT/EmbodiedGPT_Pytorch)] [[📊 Dataset](https://github.com/EmbodiedGPT/EgoCOT_Dataset)]
- **DoReMi**, *DoReMi: Grounding Language Model by Detecting and Recovering from Plan-Execution Misalignment*, 2023.07, IROS 2024. [[📄 Paper](https://arxiv.org/abs/2307.00329)] [[🌍 Website](https://sites.google.com/view/doremi-paper)]
- **ViLa**, *Look Before You Leap: Unveiling the Power of  GPT-4V in Robotic Vision-Language Planning*, 2023.11, Workshop on Vision-Language Models for Navigation and Manipulation, ICRA 2024. [[📄 Paper](https://arxiv.org/abs/2311.17842)] [[🌍 Website](https://robot-vila.github.io/)]
- **3D-VLA**, *3D-VLA: A 3D Vision-Language-Action Generative World Model*, 2024.03, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2403.09631)] [[🌍 Website](https://vis-www.cs.umass.edu/3dvla)] [[💻 Code](https://github.com/UMass-Embodied-AGI/3D-VLA)]
- **Bi-VLA**, *Bi-VLA: Vision-Language-Action Model-Based System for Bimanual Robotic Dexterous Manipulations*, 2024.05, SMC 2024. [[📄 Paper](https://arxiv.org/abs/2405.06039)]
- **RoboMamba**, *RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation*, 2024.06, NeurIPS 2024. [[📄 Paper](https://arxiv.org/abs/2406.04339)] [[🌍 Website](https://sites.google.com/view/robomamba-web)] [[💻 Code](https://github.com/lmzpai/roboMamba)]
- **ReplanVLM**, *ReplanVLM: Replanning Robotic Tasks with Visual Language Models*, 2024.07. [[📄 Paper](https://arxiv.org/abs/2407.21762v1)]
- **BUMBLE**, *BUMBLE: Unifying Reasoning and Acting with Vision-Language Models for Building-wide Mobile Manipulation*, 2024.10, ICRA 2025. [[📄 Paper](https://arxiv.org/abs/2410.06237)] [[🌍 Website](https://robin-lab.cs.utexas.edu/BUMBLE/)] [[💻 Code](https://github.com/UT-Austin-RobIn/BUMBLE)]
- **ReflectVLM**, *Reflective Planning: Vision-Language Models for Multi-Stage Long-Horizon Robotic Manipulation*, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.16707)] [[🌍 Website](https://reflect-vlm.github.io/)] [[💻 Code](https://github.com/yunhaif/reflect-vlm)] [[📊 Dataset](https://huggingface.co/datasets/yunhaif/ReflectVLM-data-expert)] [[🤗 Model](https://huggingface.co/collections/yunhaif/reflectvlm-67b95e4316ab2d5f71ad4b25)]
- **Hi Robot**, *Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models*, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.19417)] [[🌍 Website](https://www.pi.website/research/hirobot)]
- **RoboBrain**, *RoboBrain: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete*, 2025.02, CVPR 2025. [[📄 Paper](https://arxiv.org/abs/2502.21257)] [[🌍 Website](https://superrobobrain.github.io/)] [[💻 Code](https://github.com/FlagOpen/RoboBrain)] [[📊 Dataset](https://huggingface.co/datasets/BAAI/ShareRobot)]
- **$\pi_{0.5}$**, $\pi_{0.5}$*: a Vision-Language-Action Model with Open-World Generalization*, 2025.04. [[📄 Paper](https://arxiv.org/abs/2504.16054)] [[🌍 Website](https://www.physicalintelligence.company/blog/pi05)]

## Language Motion

- **RT-H**, *RT-H: Action Hierarchies Using Language*, 2024.03. [[📄 Paper](https://arxiv.org/abs/2403.01823)] [[🌍 Website](https://rt-hierarchy.github.io/)]
- **NaVILA**, *NaVILA: Legged Robot Vision-Language-Action Model for Navigation*, 2024.12, RSS 2025. [[📄 Paper](https://arxiv.org/abs/2412.04453)] [[🌍 Website](https://navila-bot.github.io/)] [[💻 Code](https://github.com/yang-zj1026/legged-loco)]

# Code as Action Tokens

- **Code as Policies**, *Code as Policies: Language Model Programs for Embodied Control*, 2022.09, ICRA 2023. [[📄 Paper](https://arxiv.org/abs/2209.07753)] [[🌍 Website](https://code-as-policies.github.io)] [[💻 Code](https://github.com/google-research/google-research/tree/master/code_as_policies)]
- **ProgPrompt**, *ProgPrompt: Generating Situated Robot Task Plans using Large Language Models*, 2022.09, ICRA 2023. [[📄 Paper](https://arxiv.org/abs/2209.11302)] [[🌍 Website](https://progprompt.github.io)] [[💻 Code](https://github.com/NVlabs/progprompt-vh)]
- **ChatGPT for Robotics**, *ChatGPT for Robotics: Design Principles and Model Abilities*, 2023.02, IEEE Access 2024. [[📄 Paper](https://arxiv.org/abs/2306.17582)] [[🌍 Website](https://www.microsoft.com/en-us/research/articles/chatgpt-for-robotics/)] [[💻 Code](https://github.com/microsoft/PromptCraft-Robotics)]
- **Text2Motion**, *Text2Motion: From Natural Language Instructions to Feasible Plans*, 2023.03, ICRL 2023. [[📄 Paper](https://arxiv.org/abs/2303.12153)] [[🌍 Website](https://sites.google.com/stanford.edu/text2motion)]
- **Instruct2Act**, *Instruct2Act: Mapping Multi-modality Instructions to Robotic Actions with Large Language Model*, 2023.05. [[📄 Paper](https://arxiv.org/abs/2305.11176)] [[💻 Code](https://github.com/OpenGVLab/Instruct2Act)]
- **RoboScript**, *RoboScript: Code Generation for Free-Form Manipulation Tasks across Real and Simulation*, 2024.02. [[📄 Paper](https://arxiv.org/abs/2402.14623)]
- **RoboCodeX**, *RoboCodeX: Multimodal Code Generation for Robotic Behavior Synthesis*, 2024.02, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2402.16117)] [[🌍 Website](https://sites.google.com/view/robocodexplus)] [[💻 Code](https://github.com/RoboCodeX-source/RoboCodeX_code)]

# Affordance as Action Tokens

## Keypoint

- **KITE**, *KITE: Keypoint-Conditioned Policies for Semantic Manipulation*, 2023.6, CoRL 2023. [[📄 Paper](https://arxiv.org/abs/2306.16605)] [[🌍 Website](https://sites.google.com/view/kite-website/home)] [[💻 Code](https://github.com/priyasundaresan/kite_keypoint_training)]
- **CoPa**, *CoPa: General Robotic Manipulation through Spatial Constraints of Parts with Foundation Models*, 2024.3, IROS 2024. [[📄 Paper](https://arxiv.org/abs/2403.08248)] [[🌍 Website](https://copa-2024.github.io/)] [[💻 Code](https://github.com/HaoxuHuang/copa)]
- **RoboPoint**, *RoboPoint: A Vision-Language Model for Spatial Affordance Prediction for Robotics*, 2024.6, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2406.10721)] [[🌍 Website](https://robo-point.github.io/)] [[💻 Code](https://github.com/wentaoyuan/RoboPoint)]
- **RAM**, *RAM: Retrieval-Based Affordance Transfer for Generalizable Zero-Shot Robotic Manipulation*, 2024.7, CoRL 2024 Oral. [[📄 Paper](https://arxiv.org/abs/2407.04689)] [[🌍 Website](https://yuxuank.com/RAM/)] [[💻 Code](https://github.com/yxKryptonite/RAM_code)]
- **ReKep**, *ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation*, 2024.9, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2409.01652)] [[🌍 Website](https://rekep-robot.github.io/)] [[💻 Code](https://github.com/huangwl18/ReKep)]
- **OmniManip**, *OmniManip: Towards General Robotic Manipulation via Object-Centric  Interaction Primitives as Spatial Constraints*, 2025.1, CVPR 2025 Highlight. [[📄 Paper](https://arxiv.org/abs/2501.03841)] [[🌍 Website](https://omnimanip.github.io/)]
- **Magma**, *Magma: A Foundation Model for Multimodal AI Agents*, 2025.2, CVPR 2025. [[📄 Paper](https://arxiv.org/abs/2502.13130)] [[🌍 Website](https://microsoft.github.io/Magma/)] [[💻 Code](https://github.com/microsoft/Magma)]
- **KUDA**, *KUDA: Keypoints to Unify Dynamics Learning and Visual Prompting for Open-Vocabulary Robotic Manipulation*, 2025.3, ICRA 2025. [[📄 Paper](https://arxiv.org/abs/2503.10546)] [[🌍 Website](https://kuda-dynamics.github.io/)] [[💻 Code](https://github.com/StoreBlank/KUDA)]

## Bounding Box

- **GPT-4V**, *GPT-4V(ision) for Robotics: Multimodal Task Planning from Human Demonstration*, 2023.11, RA-L 2024. [[📄 Paper](https://arxiv.org/abs/2311.12015)] [[🌍 Website](https://microsoft.github.io/GPT4Vision-Robot-Manipulation-Prompts/)] [[💻 Code](https://github.com/microsoft/GPT4Vision-Robot-Manipulation-Prompts)]
- **A3VLM**, *A3VLM: Actionable Articulation-Aware Vision Language Model*, 2024.6, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2406.07549)] [[💻 Code](https://github.com/changhaonan/A3VLM)]
- **DexGraspVLA**, *DexGraspVLA: A Vision-Language-Action Framework Towards General Dexterous Grasping*, 2025.2. [[📄 Paper](https://arxiv.org/abs/2502.20900)] [[🌍 Website](https://dexgraspvla.github.io/)] [[💻 Code](https://github.com/Psi-Robot/DexGraspVLA)]

## Segmentation Mask

- **MOO**, *Open-World Object Manipulation using Pre-Trained Vision-Language Models*, 2023.3, CoRL 2023. [[📄 Paper](https://arxiv.org/abs/2303.00905)] [[🌍 Website](https://robot-moo.github.io/)]
- **ROCKET-1**, *ROCKET-1: Mastering Open-World Interaction with Visual-Temporal Context Prompting*, 2024.11, CVPR 2025. [[📄 Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Cai_ROCKET-1_Mastering_Open-World_Interaction_with_Visual-Temporal_Context_Prompting_CVPR_2025_paper.html)] [[🌍 Website](https://craftjarvis.github.io/ROCKET-1)]
- **SoFar**, *SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation*, 2025.2. [[📄 Paper](https://arxiv.org/abs/2502.13143)] [[🌍 Website](https://qizekun.github.io/sofar/)] [[💻 Code](https://github.com/qizekun/SoFar)]
- **RoboDexVLM**, *RoboDexVLM: Visual Language Model-Enabled Task Planning and Motion Control for Dexterous Robot Manipulation*, 2025.3. [[📄 Paper](https://arxiv.org/abs/2503.01616)] [[🌍 Website](https://henryhcliu.github.io/robodexvlm/)]

## Affordance Map

- **CLIPort**, *CLIPort: What and Where Pathways for Robotic Manipulation*, 2021.9, CoRL 2021. [[📄 Paper](https://arxiv.org/abs/2109.12098)] [[🌍 Website](https://cliport.github.io/)] [[💻 Code](https://github.com/cliport/cliport)]
- **VoxPoser**, *VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models*, 2023.7, CoRL 2023 Oral. [[📄 Paper](https://arxiv.org/abs/2307.05973)] [[🌍 Website](https://voxposer.github.io/)] [[💻 Code](https://github.com/huangwl18/VoxPoser)]
- **ManipLLM**, *ManipLLM: Embodied Multimodal Large Language Model for Object-Centric Robotic Manipulation*, 2023.12, CVPR 2024. [[📄 Paper](https://arxiv.org/abs/2312.16217)] [[🌍 Website](https://sites.google.com/view/manipllm)] [[💻 Code](https://github.com/clorislili/ManipLLM)]
- **ManiFoundation**, *ManiFoundation Model for General-Purpose Robotic Manipulation of Contact Synthesis with Arbitrary Objects and Robots*, 2024.5, IROS 2024 Oral. [[📄 Paper](https://arxiv.org/abs/2405.06964)] [[🌍 Website](https://manifoundationmodel.github.io/)] [[💻 Code](https://github.com/NUS-LinS-Lab/ManiFM)]
- **MOKA**, *MOKA: Open-World Robotic Manipulation through Mark-Based Visual Prompting*, 2024.5, RSS 2024. [[📄 Paper](https://arxiv.org/abs/2403.03174)] [[🌍 Website](https://moka-manipulation.github.io/)] [[💻 Code](https://github.com/moka-manipulation/moka)]

# Trajectory as Action Tokens

## Robotic Manipulation

- **AVDC**, *Learning to Act from Actionless Videos through Dense Correspondences*, 2023.10, ICLR 2024 spotlight. [[📄 Paper](https://arxiv.org/abs/2310.08576)]
- **RT-Trajectory**, *RT-Trajectory: Robotic Task Generalization via Hindsight Trajectory Sketches*, 2023.11, ICLR 2024 (Spotlight). [[📄 Paper](https://arxiv.org/abs/2311.01977)] [[🌍 Website](https://rt-trajectory.github.io)]
- **ATM**, *Any-point Trajectory Modeling for Policy Learning*, 2023.12, RSS 2024. [[📄 Paper](https://arxiv.org/abs/2401.00025)] [[🌍 Website](https://xingyu-lin.github.io/atm/)] [[💻 Code](https://github.com/Large-Trajectory-Model/ATM)]
- **LLARVA**, *LLARVA: Vision-Action Instruction Tuning Enhances Robot Learning*, 2024.06, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2406.11815)] [[🌍 Website](https://llarva24.github.io)] [[💻 Code](https://github.com/Dantong88/LLARVA)] [[📊 Dataset](https://github.com/Dantong88/LLARVA/blob/main/docs/DATASET.md)]
- **Im2Flow2Act**, *Flow as the Cross-Domain Manipulation Interface*, 2024.07, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2407.15208)] [[🌍 Website](https://im-flow-act.github.io)] [[💻 Code](https://github.com/real-stanford/im2Flow2Act)]
- **FLIP**, *FLIP : Flow-Centric Generative Planning as General-Purpose Manipulation World Model*, 2024.12, ICLR 2025 Poster. [[📄 Paper](https://arxiv.org/abs/2412.08261)] [[🌍 Website](https://nus-lins-lab.github.io/flipweb/)] [[💻 Code](https://github.com/HeegerGao/FLIP)]
- **HAMSTER**, *HAMSTER: Hierarchical Action Models for Open-World Robot Manipulation*, 2025.02, ICLR 2025. [[📄 Paper](https://arxiv.org/abs/2502.05485)] [[🌍 Website](https://hamster-robot.github.io)]
- **ARM4R**, *Pre-training Auto-regressive Robotic Models with 4D Representations*, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.13142)]
- **Magma**, *Magma: A foundation model for multimodal AI agents*, 2025.02, CVPR 2025. [[📄 Paper](https://arxiv.org/abs/2502.13130)] [[🌍 Website](https://microsoft.github.io/Magma/)] [[💻 Code](https://github.com/microsoft/Magma)] [[🤗 Model](https://huggingface.co/microsoft/Magma-8B)]

## Autonomous Driving

- **DriveVLM**, *DriveVLM: The Convergence of Autonomous Driving and Large Vision-Language Models*, 2024.02, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2402.12289)] [[🌍 Website](https://tsinghua-mars-lab.github.io/DriveVLM/)]
- **CoVLA**, *CoVLA: Comprehensive Vision-Language-Action Dataset for Autonomous Driving*, 2024.08, WACV 2025 Oral. [[📄 Paper](https://arxiv.org/abs/2408.10845)] [[🌍 Website](https://turingmotors.github.io/covla-ad/)] [[📊 Dataset](https://huggingface.co/datasets/turing-motors/CoVLA-Dataset)]
- **EMMA**, *EMMA: End-to-End Multimodal Model for Autonomous Driving*, 2024.10. [[📄 Paper](https://arxiv.org/abs/2410.23262)]
- **VLM-E2E**, *VLM-E2E: Enhancing End-to-End Autonomous Driving with Multimodal Driver Attention Fusion*, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.18042)]
- **WAM-Flow**, *WAM-Flow: Parallel Coarse-to-Fine Motion Planning via Discrete Flow Matching for Autonomous Driving*, CVPR 2026. [[📄 Paper](https://arxiv.org/abs/2512.06112)] [[💻 Code](https://github.com/fudan-generative-vision/WAM-Flow)] [[🤗 Model](https://huggingface.co/fudan-generative-ai/WAM-Flow)]

# Goal State as Action Tokens

## Single-Frame Image / Point Cloud

* **SuSIE**, *Zero-Shot Robotic Manipulation with Pretrained Image-Editing Diffusion Models*, 2023.10, ICLR 2024. [[📄 Paper](https://arxiv.org/abs/2310.10639)] [[🌍 Website](https://rail-berkeley.github.io/susie/)] [[💻 Code](https://github.com/kvablack/susie)]
* **3D-VLA**, *3D-VLA: A 3D Vision-Language-Action Generative World Model*, 2024.03, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2403.09631)] [[🌍 Website](https://vis-www.cs.umass.edu/3dvla/)]
* **CoTDiffusion**, *Generate Subgoal Images before Act: Unlocking the Chain-of-Thought Reasoning in Diffusion Model for Robot Manipulation with Multimodal Prompts*, 2024.06, CVPR 2024. [[📄 Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ni_Generate_Subgoal_Images_before_Act_Unlocking_the_Chain-of-Thought_Reasoning_in_CVPR_2024_paper.html)] [[🌍 Website](https://cotdiffusion.github.io/)]
* **CoT-VLA**, *CoT-VLA: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models*, 2025.03, CVPR 2025. [[📄 Paper](https://arxiv.org/abs/2503.22020)] [[🌍 Website](https://cot-vla.github.io/)]

## Multi-Frame Video

* **UniPi**, *Learning Universal Policies via Text-Guided Video Generation*, 2023.02, NeurIPS 2023 spotlight. [[📄 Paper](https://arxiv.org/abs/2302.00111)] [[🌍 Website](https://universal-policy.github.io/unipi/)]
* **AVDC**, *Learning to Act from Actionless Videos through Dense Correspondences*, 2023.10, ICLR 2024 spotlight. [[📄 Paper](https://arxiv.org/abs/2310.08576)] [[🌍 Website](https://flow-diffusion.github.io/)] [[💻 Code](https://github.com/flow-diffusion/AVDC)]
* **VLP**, *Video Language Planning*, 2023.10. [[📄 Paper](https://arxiv.org/abs/2310.10625)] [[🌍 Website](https://video-language-planning.github.io/)] [[💻 Code](https://github.com/video-language-planning/vlp_code)]
* **Gen2Act**, *Gen2Act: Human Video Generation in Novel Scenarios enables Generalizable Robot Manipulation*, 2024.09, CoRL-X-Embodiment-WS 2024. [[📄 Paper](https://arxiv.org/abs/2409.16283)] [[🌍 Website](https://homangab.github.io/gen2act/)]
* **Video Prediction Policy**, *Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations*, 2024.12, ICML 2025 Spotlight. [[📄 Paper](https://arxiv.org/abs/2412.14803)] [[🌍 Website](https://video-prediction-policy.github.io/)] [[💻 Code](https://github.com/roboterax/video-prediction-policy)]
* **FLIP**, *FLIP: Flow-Centric Generative Planning as General-Purpose Manipulation World Model*, 2024.12, ICLR 2025 [[📄 Paper](https://arxiv.org/abs/2412.08261)] [[🌍 Website](https://nus-lins-lab.github.io/flipweb/)] [[💻 Code](https://github.com/HeegerGao/FLIP)]
* **GEVRM**, *GEVRM: Goal-Expressive Video Generation Model For Robust Visual Manipulation*, 2025.02, ICLR 2025. [[📄 Paper](https://arxiv.org/abs/2502.09268)]

# Latent Representation as Action Tokens

- **OmniJARVIS**, *OmniJARVIS: Unified Vision-Language-Action Tokenization Enables Open-World Instruction Following Agents*, 2024.07, NeurIPS 2024. [[📄 Paper](https://arxiv.org/abs/2407.00114)] [[🌍 Website](https://omnijarvis.github.io)] [[💻 Code](https://github.com/CraftJarvis/OmniJarvis)] [[📊 Dataset](https://huggingface.co/datasets/zhwang4ai/Minecraft-EmbodiedQA-300k)]
- **QueST**, *QueST: Self-Supervised Skill Abstractions for Learning Continuous Control*, 2024.07, NeurIPS 2024. [[📄 Paper](https://arxiv.org/abs/2407.15840)] [[🌍 Website](https://quest-model.github.io)] [[💻 Code](https://github.com/pairlab/QueST)]
- **LAPA**, *LAPA: Latent Action Pretraining from Videos*, 2024.10, ICLR 2025. [[📄 Paper](https://arxiv.org/abs/2410.11758)] [[🌍 Website](https://latentactionpretraining.github.io)] [[💻 Code](https://github.com/LatentActionPretraining/LAPA)] [[🤗 Model](https://huggingface.co/latent-action-pretraining/LAPA-7B-openx)]
- **GROOT-2**, *GROOT-2: Weakly Supervised Multi-Modal Instruction Following Agents*, 2024.12, ICLR 2025. [[📄 Paper](https://arxiv.org/abs/2412.10410)]
- **GO-1**, *AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.06669)] [[🌍 Website](https://agibot-world.com)] [[💻 Code](https://github.com/OpenDriveLab/AgiBot-World)] [[📊 Dataset](https://huggingface.co/agibot-world)]
- **UniVLA**, *UniVLA: Learning to Act Anywhere with Task-centric Latent Actions*, 2025.05, RSS2025. [[📄 Paper](https://arxiv.org/abs/2505.06111)] [[💻 Code](https://github.com/OpenDriveLab/UniVLA)] [[🤗 Model](https://github.com/OpenDriveLab/UniVLA#ckpts)]

# Raw Action as Action Tokens

- **LangLfP**, *Language-Conditioned Imitation Learning over Unstructured Data*, 2020.05, RSS 2021. [[📄 Paper](https://arxiv.org/abs/2005.07648)] [[🌍 Website](https://language-play.github.io)]
- **BC-Z**, *Zero-Shot Task Generalization with Robotic Imitation Learning*, 2022.02, CoRL 2021. [[📄 Paper](https://arxiv.org/abs/2202.02005)] [[🌍 Website](https://sites.google.com/view/bc-z/home?pli=1)] [[💻 Code](https://github.com/google-research/tensor2robot/tree/master/research/bcz)]
- **Gato**, *A Generalist Agent*, 2022.05, TMLR 2022. [[📄 Paper](https://arxiv.org/abs/2205.06175)] [[🌍 Website](https://deepmind.google/discover/blog/a-generalist-agent/)]
- **VIMA**, *VIMA: General Robot Manipulation with Multimodal Prompts*, 2022.10, ICML 2023. [[📄 Paper](https://arxiv.org/abs/2210.03094)] [[🌍 Website](https://vimalabs.github.io/)] [[💻 Code](https://github.com/vimalabs/VIMA)] [[🤗 Model](https://huggingface.co/VIMA/VIMA)]
- **RT-1**, *RT-1: Robotics Transformer for Real-World Control at Scale*, 2022.12, RSS 2023. [[📄 Paper](https://arxiv.org/abs/2212.06817)] [[🌍 Website](https://robotics-transformer1.github.io/)] [[💻 Code](https://github.com/google-research/robotics_transformer)]
- **RT-2**, *RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control*, 2023.07, CoRL 2023. [[📄 Paper](https://arxiv.org/abs/2307.15818)] [[🌍 Website](https://robotics-transformer2.github.io/)]
- **RT-X**, *Open X-Embodiment: Robotic Learning Datasets and RT-X Models*, 2023.10, ICRA 2024. [[📄 Paper](https://arxiv.org/abs/2310.08864)] [[🌍 Website](https://robotics-transformer-x.github.io)] [[💻 Code](https://github.com/google-deepmind/open_x_embodiment)]
- **RoboFlamingo**, *Vision-Language Foundation Models as Effective Robot Imitators*, 2023.11, ICLR 2024. [[📄 Paper](https://arxiv.org/abs/2311.01378)] [[🌍 Website](https://roboflamingo.github.io)] [[💻 Code](https://github.com/RoboFlamingo/RoboFlamingo)] [[🤗 Model](https://huggingface.co/roboflamingo/RoboFlamingo)]
- **LEO**, *An Embodied Generalist Agent in 3D World*, 2023.11, ICML 2024. [[📄 Paper](https://arxiv.org/abs/2311.12871)] [[🌍 Website](https://embodied-generalist.github.io/)] [[💻 Code](https://github.com/embodied-generalist/embodied-generalist?tab=readme-ov-file)]
- **GR-1**, *Unleashing Large-Scale Video Generative Pre-training for Visual Robot Manipulation*, 2023.12, ICLR 2024. [[📄 Paper](https://arxiv.org/abs/2312.13139)] [[🌍 Website](https://gr1-manipulation.github.io/)] [[💻 Code](https://github.com/bytedance/GR-1)]
- **Octo**, *Octo: An Open-Source Generalist Robot Policy*, 2024.05, ICRA 2024. [[📄 Paper](https://arxiv.org/abs/2405.12213)] [[🌍 Website](https://octo-models.github.io)] [[💻 Code](https://github.com/octo-models/octo)] [[🤗 Model](https://huggingface.co/rail-berkeley)]
- **OpenVLA**, *OpenVLA: An open-source vision-language-action model*, 2024.06, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2406.09246)] [[🌍 Website](https://openvla.github.io/)] [[💻 Code](https://github.com/openvla/openvla)] [[🤗 Model](https://huggingface.co/openvla)]
- **TinyVLA**, *TinyVLA: Towards Fast, Data-Efficient Vision-Language-Action Models for Robotic Manipulation*, 2024.09, RA-L 2025. [[📄 Paper](https://arxiv.org/abs/2409.12514)] [[🌍 Website](https://tiny-vla.github.io/)] [[💻 Code](https://github.com/liyaxuanliyaxuan/TinyVLA)]
- **HiRT**, *HiRT: Enhancing Robotic Control with Hierarchical Robot Transformers*, 2024.09, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2410.05273)]
- **GR-2**, *GR-2: A Generative Video-Language-Action Model with Web-Scale Knowledge for Robot Manipulation*, 2024.10. [[📄 Paper](https://arxiv.org/abs/2410.06158v1)] [[🌍 Website](https://gr2-manipulation.github.io/)]
- **RDT-1B**, *RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation*, 2024.10, ICLR 2025. [[📄 Paper](https://arxiv.org/abs/2410.07864)] [[🌍 Website](https://rdt-robotics.github.io/rdt-robotics/)] [[💻 Code](https://rdt-robotics.github.io/rdt-robotics/)] [[🤗 Model](https://huggingface.co/robotics-diffusion-transformer/rdt-1b)]
- **$\pi_0$**, *A Vision-Language-Action Flow Model for General Robot Control*, 2024.10. [[📄 Paper](https://arxiv.org/abs/2410.24164)] [[🌍 Website](https://www.physicalintelligence.company/blog/pi0)] [[🤗 Model](https://huggingface.co/lerobot/pi0)]
- **CogACT**, *CogACT: A Foundational Vision-Language-Action Model for Synergizing Cognition and Action in Robotic Manipulation*, 2024.11. [[📄 Paper](https://arxiv.org/abs/2411.19650)] [[🌍 Website](https://cogact.github.io/)] [[💻 Code](https://github.com/microsoft/CogACT?tab=readme-ov-file)] [[🤗 Model](https://huggingface.co/CogACT/CogACT-Base)]
- **$\pi_0$-FAST**, *FAST: Efficient Action Tokenization for Vision-Language-Action Models*, 2025.01. [[📄 Paper](https://arxiv.org/abs/2501.09747)] [[🌍 Website](https://www.pi.website/research/fast)] [[🤗 Model](https://huggingface.co/lerobot/pi0fast_base)]
- **UniAct**, *Universal Actions for Enhanced Embodied Foundation Models*, 2025.01, CVPR 2025. [[📄 Paper](https://arxiv.org/abs/2501.10105)] [[🌍 Website](https://2toinf.github.io/UniAct/)] [[💻 Code](https://github.com/2toinf/UniAct)]
- **OpenVLA-OFT**, *Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success*, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.19645)] [[🌍 Website](https://openvla-oft.github.io)] [[💻 Code](https://github.com/moojink/openvla-oft)]
- **JARVIS-VLA**, *Post-Training Large-Scale Vision Language Models to Play Visual Games with Keyboards and Mouse*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.16365)] [[🌍 Website](https://craftjarvis.github.io/JarvisVLA/)] [[💻 Code](https://github.com/CraftJarvis/JarvisVLA)] [[🤗 Model](https://huggingface.co/collections/CraftJarvis/jarvis-vla-v1-67dc157a99d011efd7d7f7e4)]
- **HybridVLA**, *HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.10631)] [[🌍 Website](https://hybrid-vla.github.io)] [[💻 Code](https://github.com/PKU-HMI-Lab/Hybrid-VLA)]
- **MoManipVLA**, *MoManipVLA: Transferring Vision-Language-Action Models for General Mobile Manipulation*, 2025.03, CVPR 2025. [[📄 Paper](https://arxiv.org/abs/2503.13446)]
- **GR00T N1**, *GR00T N1: An Open Foundation Model for Generalist Humanoid Robots*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.14734)] [[🌍 Website](https://developer.nvidia.com/isaac/gr00t)] [[💻 Code](https://github.com/NVIDIA/Isaac-GR00T)] [[🤗 Model](https://huggingface.co/nvidia/GR00T-N1.5-3B)]
- **$\pi_0$+KI**, *Knowledge Insulating Vision-Language-Action Models: Train Fast, Run Fast, Generalize Better*, 2025.05. [[📄 Paper](https://arxiv.org/abs/2505.23705)] [[🌍 Website](https://www.physicalintelligence.company/research/knowledge_insulation)]
- **RTC**, *Real-Time Execution of Action Chunking Flow Policies*, 2025.06. [[📄 Paper](https://arxiv.org/abs/2506.07339)] [[🌍 Website](https://www.pi.website/research/real_time_chunking)]

# Reasoning as Action Tokens

- **Inner Monologue**, *Inner Monologue: Embodied Reasoning through Planning with Language Models*, 2022.07, CoRL 2022. [[📄 Paper](https://arxiv.org/abs/2207.05608)] [[🌍 Website](https://innermonologue.github.io/)]
- **DriveVLM**, *DriveVLM: The Convergence of Autonomous Driving and Large Vision-Language Models*, 2024.02, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2402.12289)] [[🌍 Website](https://tsinghua-mars-lab.github.io/DriveVLM/)]
- **ECoT**, *Robotic Control via Embodied Chain-of-Thought Reasoning*, 2024.07, CoRL 2024. [[📄 Paper](https://arxiv.org/abs/2407.08693)] [[🌍 Website](https://embodied-cot.github.io/)]
- **RAD**, *Action-Free Reasoning for Policy Generalization*, 2025.02. [[📄 Paper](https://arxiv.org/abs/2502.03729)] [[🌍 Website](https://rad-generalization.github.io/)]
- **AlphaDrive**, *AlphaDrive: Unleashing the Power of VLMs in Autonomous Driving via Reinforcement Learning and Reasoning*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.07608)] [[🌍 Website](https://github.com/hustvl/AlphaDrive)]
- **Cosmos-Reason1**, *Cosmos-Reason1: From Physical Common Sense To Embodied Reasoning*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.15558)] [[🌍 Website](https://research.nvidia.com/labs/dir/cosmos-reason1/)] [[💻 Code](https://github.com/nvidia-cosmos/cosmos-reason1?tab=readme-ov-file)]

# Scalable Data Sources

## Bottom Layer: Web Data and Human Video

- **Something-Something V2**, *The" something something" video database for learning and evaluating visual common sense*, 2017.06. [[📄 Paper](https://arxiv.org/abs/1706.04261)] [[🌍 Website](https://www.qualcomm.com/developer/software/something-something-v-2-dataset)]
- **EPIC-KITCHENS-100**, *Scaling Egocentric Vision: The EPIC-KITCHENS Dataset*, 2018.04. [[📄 Paper](https://arxiv.org/abs/1804.02748)] [[🌍 Website](https://epic-kitchens.github.io/2020-100)]
- **Ego4D**, *Ego4D: Around the World in 3,000 Hours of Egocentric Video*, 2021.10. [[📄 Paper](https://arxiv.org/abs/2110.07058)] [[🌍 Website](https://ego4d-data.org)]
- **Ego-Exo4D**, *Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives*, 2023.11. [[📄 Paper](https://arxiv.org/abs/2311.18259)] [[🌍 Website](https://ego-exo4d-data.org/)]

## Middle Layer: Synthetic and Simulation Data

- **MimicGen**, *MimicGen: A Data Generation System for Scalable Robot Learning using Human Demonstrations*, 2023.10, CoRL 2023. [[📄 Paper](https://arxiv.org/abs/2310.17596)]
- **RoboCase**, *RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots*, 2024.06, RSS 2024. [[📄 Paper](https://arxiv.org/abs/2406.02523)] [[🌍 Website](https://robocasa.ai/)] [[💻 Code](https://github.com/robocasa/robocasa)]
- **DexMimicGen**, *DexMimicGen: Automated Data Generation for  Bimanual Dexterous Manipulation via Imitation Learning*, 2024.10, ICRA 2025. [[📄 Paper](https://arxiv.org/abs/2410.24185)] [[🌍 Website](https://dexmimicgen.github.io)]
- **AgiBot DigitalWorld**, *AgiBot DigitalWorld*, 2025.02. [[🌍 Website](https://agibot-digitalworld.com/)]

## Top Layer: Real-world Robot Data

- **nuScenes**, *nuScenes: A multimodal dataset for autonomous driving*, 2019.03, CVPR 2020. [[📄 Paper](https://arxiv.org/abs/1903.11027)] [[🌍 Website](https://www.nuscenes.org/)] [[💻 Code](https://github.com/nutonomy/nuscenes-devkit)]
- **WOMD**, *Large Scale Interactive Motion Forecasting for Autonomous Driving: The Waymo Open Motion Dataset*, 2021.04, ICCV 2021. [[📄 Paper](https://arxiv.org/abs/2104.10133)] [[🌍 Website](https://waymo.com/open/)] [[💻 Code](https://github.com/waymo-research/waymo-open-dataset)]
- **RT-1**, *RT-1: Robotics Transformer for Real-World Control at Scale*, 2022.12. [[📄 Paper](https://arxiv.org/abs/2212.06817)] [[🌍 Website](https://robotics-transformer1.github.io/)]
- **RH20T**, *RH20T: A Comprehensive Robotic Dataset for Learning Diverse Skills in One-Shot*, 2023.06, ICRA 2024. [[📄 Paper](https://arxiv.org/abs/2307.00595)] [[🌍 Website](https://rh20t.github.io)]
- **BridgeData V2**, *BridgeData V2: A Dataset for Robot Learning at Scale*, 2023.08, CoRL 2o23. [[📄 Paper](https://arxiv.org/abs/2308.12952)] [[🌍 Website](https://rail-berkeley.github.io/bridgedata/)]
- **OXE**, *Open X-Embodiment: Robotic Learning Datasets and RT-X Models*, 2023.10, ICRA 2024. [[📄 Paper](https://arxiv.org/abs/2310.08864)] [[🌍 Website](https://robotics-transformer-x.github.io)]
- **HoNY**, *On Bringing Robots Home*, 2023.11. [[📄 Paper](https://arxiv.org/abs/2311.16098)] [[🌍 Website](https://dobb-e.com)]
- **DROID**, *DROID: A Large-Scale In-the-Wild Robot Manipulation Dataset*, 2024.03, RSS 2024. [[📄 Paper](https://arxiv.org/abs/2403.12945)] [[🌍 Website](https://huggingface.co/KarlP/droid)]
- **CoVLA**, *CoVLA: Comprehensive Vision-Language-Action Dataset for Autonomous Driving*, 2024.08, WACV 2025. [[📄 Paper](https://arxiv.org/abs/2408.10845)] [[🌍 Website](https://turingmotors.github.io/covla-ad/)]
- **RoboMIND**, *RoboMIND: Benchmark on Multi-embodiment Intelligence Normative Data for Robot Manipulation*, 2024.12, RSS 2025. [[📄 Paper](https://arxiv.org/abs/2412.13877)] [[🌍 Website](https://x-humanoid-robomind.github.io/)]
- **AgiBot World**, *AgiBot World Colosseo: A Large-scale Manipulation Platform for Scalable and Intelligent Embodied Systems*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.06669)] [[🌍 Website](https://agibot-world.com/)] [[💻 Code](https://github.com/OpenDriveLab/AgiBot-World)]

# Related Surveys

- *Robot Learning in the Era of Foundation Models: A Survey*, 2023.11, Neurocomputing Volume 638. [[📄 Paper](https://arxiv.org/abs/2311.14379)]
- *A Survey on Robotics with Foundation Models: toward Embodied AI*, 2024.02. [[📄 Paper](https://arxiv.org/abs/2402.02385)]
- *A Survey on Integration of Large Language Models with Intelligent Robots*, 2024.04, Intelligent Service Robotics 2024. [[📄 Paper](https://arxiv.org/abs/2404.09228)]
- *What Foundation Models can Bring for Robot Learning in Manipulation: A Survey*, 2024.04. [[📄 Paper](https://arxiv.org/abs/2404.18201)]
- *A Survey on Vision-Language-Action Models for Embodied AI*, 2024.05. [[📄 Paper](https://arxiv.org/abs/2405.14093)]
- *Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI*, 2024.07. [[📄 Paper](https://arxiv.org/abs/2407.06886)]
- *Exploring Embodied Multimodal Large Models: Development, Datasets, and Future Directions*, 2025.02, Information Fusion Volume 122. [[📄 Paper](https://arxiv.org/abs/2502.15336)]
- *Generative Artificial Intelligence in Robotic Manipulation: A Survey*, 2025.03. [[📄 Paper](https://arxiv.org/abs/2503.03464)]
- *OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation*, 2025.05. [[📄 Paper](https://arxiv.org/abs/2505.03912)]
- *Vision-Language-Action Models: Concepts, Progress, Applications and Challenges*, 2025.05. [[📄 Paper](https://arxiv.org/abs/2505.04769)]
