# MMATrans
MMATrans: Muscle Movement Aware Representation Learning for Facial Expression Recognition via Transformers

## 📑 Abstract
How to automatically recognize facial expression has caused concerns in industrial human–robot interaction. However, facial expression recognition (FER) is susceptible to problems, such as occlusion, arbitrary orientations, and illumination. To effectively address these challenges in FER, we present a novel  **facial muscle movement aware representation learning** that can learn the semantic relationships of facial muscle movements in facial expression images. Two key findings are revealed:  **1) muscle movements from different facial regions often show semantic relationships**; and  **2) not all facial muscle regions have equal contributions for different facial expressions**. On this basis, this model presents two novel modules, namely, discriminative feature generation (DFG) and muscle relationship mining (MRM). Specifically, in DFG, the memory of our model for mislabeling decreases. In MRM, muscle–motion interaction among diverse facial regions is learned through visual transformers (MMATrans). Experiments on three in-the-wild FER datasets (RAF-DB, FERPlus, and AffectNet) show that our MMATrans yields better performance compared with state-of-the-art methods.

## 🌟 Key Contributions
1) Inspired by our key findings, including muscle–motion interaction(correlation, mutual exclusion, andsymmetry) and critical minority regions, an effective muscle movement aware transformer (MMATrans) model is proposed to mitigate problems, such as occlusion, arbitrary orientations, and illumination.
2) The DFG module is designed to construct discriminative feature representations and hence weaken the memory of our model for mislabeling. Then, MRM module is leveraged to learn semantic relationships among muscle movements which can help to infer the missing facial regions.
3) A novel token-based representation learning is proposed to infer the missing facial regions by modeling the semantic relationships of facial muscle movements. DTS is introduced in MMATrans that can remove the interference of redundant information and focus on critical minority facial regions.
4) Achieve SOTA performance on three wild FER datasets (RAF-DB: 89.67%, FERPlus: 90.32%, AffectNet: 64.89%)

## 📊 Datasets
This study conducted comparative experiments on three mainstream in-the-wild facial expression recognition (FER) datasets namely, **RAF-DB, FERPlus, and AffectNet**. All datasets adopted the official training/test splits, and facial images were uniformly preprocessed to 224×224 resolution.


## Citation
```bibtex
@article{10636220,
  author={Liu, Hai and Zhou, Qiyun and Zhang, Cheng and Zhu, Junyan and Liu, Tingting and Zhang, Zhaoli and Li, You-Fu},
  journal={IEEE Transactions on Industrial Informatics}, 
  title={MMATrans: Muscle Movement Aware Representation Learning for Facial Expression Recognition via Transformers}, 
  year={2024},
  volume={20},
  number={12},
  pages={13753-13764},
  keywords={Feature extraction;Facial muscles;Muscles;Visualization;Transformers;Semantics;Representation learning;Critical minority;facial expression recognition (FER);facial muscle movement;human–robot interaction;semantic relationships;visual transformer},
  doi={10.1109/TII.2024.3431640}}
