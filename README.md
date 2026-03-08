# MMATrans
MMATrans: Muscle Movement Aware Representation Learning for Facial Expression Recognition via Transformers

## Abstract
How to automatically recognize facial expression has caused concerns in industrial human–robot interaction. However, facial expression recognition (FER) is susceptible to problems, such as occlusion, arbitrary orientations, and illumination. To effectively address these challenges in FER, we present a novel facial muscle movement aware representation learning that can learn the semantic relationships of facial muscle movements in facial expression images. Two key findings are revealed: 1) muscle movements from different facial regions often show semantic relationships; and 2) not all facial muscle regions have equal contributions for different facial expressions. On this basis, this model presents two novel modules, namely, discriminative feature generation (DFG) and muscle relationship mining (MRM). Specifically, in DFG, the memory of our model for mislabeling decreases. In MRM, muscle–motion interaction among diverse facial regions is learned through visual transformers (MMATrans). Experiments on three in-the-wild FER datasets (RAF-DB, FERPlus, and AffectNet) show that our MMATrans yields better performance compared with state-of-the-art methods.

## Citation
```bibtex
@ARTICLE{10636220,
  author={Liu, Hai and Zhou, Qiyun and Zhang, Cheng and Zhu, Junyan and Liu, Tingting and Zhang, Zhaoli and Li, You-Fu},
  journal={IEEE Transactions on Industrial Informatics}, 
  title={MMATrans: Muscle Movement Aware Representation Learning for Facial Expression Recognition via Transformers}, 
  year={2024},
  volume={20},
  number={12},
  pages={13753-13764},
  keywords={Feature extraction;Facial muscles;Muscles;Visualization;Transformers;Semantics;Representation learning;Critical minority;facial expression recognition (FER);facial muscle movement;human–robot interaction;semantic relationships;visual transformer},
  doi={10.1109/TII.2024.3431640}}
