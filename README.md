# CLIP-like models

|  Name    |  Type    | Res. | (Zero-Shot) IN-1K acc. |
| :--- | :--- | :--: | :--: |
|  CLIP (OpenAI) [[code]](https://github.com/openai/CLIP) [[paper]](https://arxiv.org/abs/2103.00020)    | ViT-B/32 | 224px | 63.2% |
| | ViT-B/16 | 224px | 68.6% |
| | ViT-L/14 | 224px | 75.3% |
| | RN50 | 224px | 59.6% |
| | RN101 | 224px | 62.2% |
| | RN50x4 | 224px | 65.8% |
| | RN50x16 | 224px | 70.5% |
| | RN50x64 | 224px | 73.6% |
| | ViT-L/14@336px | 336px | 76.2% |
|  OpenCLIP [[code]](https://github.com/mlfoundations/open_clip) [[paper]](https://arxiv.org/abs/2212.07143) | ViT-B/32 | 256px | 72.8% |
| | ViT-B/16	|224px	|73.5%|
| | ViT-L/14	|224px	|75.3%|
| | ViT-H/14	|224px	|78.0%|
| | ViT-L/14	|224px	|79.2%|
| | ViT-G/14	|224px	|80.1%|
| | ViT-L/14	|224px	|75.5%|
| | ConvNext-Base	|256px |71.5%|
| | ConvNext-Large |320px |76.9%|
| | ConvNext-XXLarge |256px |79.5%|
|  EVA-CLIP [[code]](https://github.com/baaivision/EVA) [[paper]](https://arxiv.org/abs/2303.15389) | EVA01_CLIP_g_14_psz14_s11B | 224px | 78.5% |
| | EVA01_CLIP_g_14_plus_psz14_s11B | 224px | 79.3% |
| | EVA02_CLIP_B_psz16_s8B | 224px | 74.7% |
| | EVA02_CLIP_L_psz14_s4B | 224px | 79.8% |
| | EVA02_CLIP_L_336_psz14_s6B | 336px | 80.4% |
| | EVA02_CLIP_E_psz14_s4B | 224px | 81.9% |
| | EVA02_CLIP_E_psz14_plus_s9B | 224px | 82.0% |
|  SigLIP [[code]](https://github.com/google-research/big_vision) [[paper]](https://arxiv.org/abs/2303.15343) | xx | 224px | ?|
|  CLIPA [[code]](https://github.com/UCSC-VLAA/CLIPA) [[paper]](https://arxiv.org/abs/2305.07017) | CLIPA-B/16 | 224px | 63.2% |
| | CLIPA-L/14| 224px | 80.3% |
| | CLIPA-H/14| 224px | 81.8% |
| | CLIPA-G/14| 224px | 83.0% |
|  MetaCLIP [[code]](https://github.com/facebookresearch/MetaCLIP) [[paper]](https://arxiv.org/abs/2309.16671) | MetaCLIP-B32-400M| 224px | 65.5% |
| | MetaCLIP-B16-400M| 224px | 70.8% |
| | MetaCLIP-L14-400M| 224px | 76.2% |
| | MetaCLIP-B32-2.5B| 224px | 67.6% |
| | MetaCLIP-B16-2.5B| 224px | 72.1% |
| | MetaCLIP-L14-2.5B| 224px | 79.2% |
| | MetaCLIP-H14-2.5B| 224px | 80.5% |
| | MetaCLIP-G14-2.5B| 224px | ? |
