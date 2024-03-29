# PureMM
PureMM is developed by TencentQQ Multimedia Research Team.

# Release
* [2024-01-26]：v1.3 model weight released.  
* [2024-01-17]：v1.2 model weight released.  
* [2023-12-28]：Model and inference code released.  

# Install
**`pip install -e .`**

# Preparation
* The latest version of model weight should download from huggingface:
https://huggingface.co/Q-MM/PureMM/tree/main


# Evaluation
Before evaluation, please download the MME benchmark files [MME](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation) into the mme_bench directory. <br>
Then run the cmd: <br>

**`sh eval/eval_mme.sh`**

# MME benchmark
PureMM achieved 1686.52 points on perception score, which was top1 on MME benchmark on 2024-01-21. <br>

<img width="897" alt="企业微信截图_262e4ae1-bfa3-43f5-bcf6-f9abcbf2d533" src="https://github.com/Q-MM/PureMM/assets/14832463/3a1cca00-5365-4242-8352-2b6a49c32ed9">



# Acknowledgments
* [LLaVA](https://github.com/haotian-liu/LLaVA): the codebase we built upon. Thanks for their wonderful work.
* [Vicuna](https://github.com/lm-sys/FastChat): the amazing open-sourced large language model!
