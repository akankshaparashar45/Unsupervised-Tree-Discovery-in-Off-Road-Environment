# Unsupervised-Tree-Discovery-in-Off-Road-Environment
Unsupervised Object Discovery | Computer Vision | Vision Transformer
# Abstract
Unsupervised object discovery in off-road environments is challenging due to clutter, occlusions, and lack of labeled data. This work uses a DINO-pretrained Vision Transformer with attention transfer to focus on relevant regions. Feature upsampling is applied to recover fine spatial details, while depth information improves foreground-background separation. The framework is evaluated on simulated and real-world datasets, generating pseudo-masks for detector training. Results show that bounding-box guidance and depth cues enhance localization, though MaskCut remains sensitive to clutter and occlusion. Overall, the study demonstrates the potential and limitations of unsupervised pipelines in complex off-road scenarios.
# Problem Statement
In off-road environments, the background often dominates the image, making it difficult to distinguish and localize target objects such as tree trunks. Existing self-supervised object discovery methods struggle in such scenarios due to occlusions, overlapping structures, and complex natural clutter. Additionally, the lack of diverse annotated off-road datasets under varying conditions limits the effectiveness of supervised approaches. This research addresses these challenges using unsupervised and weakly supervised techniques, supported by synthetic data generation. It also emphasizes domain generalization to ensure robustness when transferring from simulated training data to real-world environments.
# Proposed Approach
This work proposes an unsupervised pipeline for object discovery in complex off-road environments using transformer-based features, feature upsampling, and depth integration.

- Use **DINO-pretrained Vision Transformer (ViT)** to extract semantic features  
- Apply **attention transfer with bounding-box guidance** to focus on the region of interest  
- Use **FeatUp** to upsample features and recover fine spatial details  
- Construct an **affinity matrix** and apply **MaskCut** for foreground-background partitioning  
- Integrate **depth information** to improve separation in visually similar regions  
- Generate **pseudo-masks** for object localization and downstream tasks  

**Key Idea:** Combine semantic features, spatial refinement, and geometric cues to improve unsupervised object discovery in cluttered off-road scenes.
# Methodology
asdf
# Repository Structure
asdf
# Installation
asdf
# Usage
asdf
# Experiments
asdf
# Results
-- Quatitative Results
-- Quantiitative Results
# Evaluation Metrics
asdf
# Limitations
asdf
# Future Work
asdf
# References
- [Localizing Objects with Self-Supervised Transformers and no Labels (Siméoni et al., 2021)](https://arxiv.org/abs/2109.14279)
- [Self-Supervised Transformers for Unsupervised Object Discovery using Normalized Cut (Wang et al., 2022)](https://arxiv.org/abs/2202.11539)
- [MOST: Multiple Object Localization with Self-supervised Transformers for Object Discovery (Rambhatla et al., 2023)](https://arxiv.org/abs/2304.05387)
- [Cut and Learn for Unsupervised Object Detection and Instance Segmentation (Wang et al., 2023)](https://arxiv.org/abs/2301.11320)
- [FeatUp: A Model-Agnostic Framework for Features at Any Resolution (Fu et al., 2024)](https://arxiv.org/abs/2403.10516)
- [CuVLER: Enhanced Unsupervised Object Discoveries through Exhaustive Self-Supervised Transformers (Arica et al., 2024)](https://arxiv.org/abs/2403.07700v1)
