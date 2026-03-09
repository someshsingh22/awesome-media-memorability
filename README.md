# Awesome Media Memorability [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of research papers, datasets, tools, and resources for understanding and predicting what makes visual content memorable

Media memorability is the study of what makes images, videos, and other visual content stick in human memory. Research has shown that memorability is an intrinsic property of visual content that is consistent across viewers, making it measurable and predictable using computational methods. This awesome list compiles the most important papers, datasets, and resources in the field.

## Contents

- [Surveys and Reviews](#surveys-and-reviews)
- [Prediction](#prediction)
- [Generation and Modification](#generation-and-modification)
- [Datasets](#datasets)
- [Workshops and Challenges](#workshops-and-challenges)
- [Contributing](#contributing)

## Surveys and Reviews

- [**Memorability: An image-computable measure of information utility**](https://link.springer.com/chapter/10.1007/978-3-030-81465-6_8) - Comprehensive overview of memorability as a computational measure, covering algorithms, visualizations, and applications across images, faces, objects, and videos. *Bylinskii et al.* (Book Chapter, 2021)

- [**Understanding Image Memorability**](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(20)30095-9) - Review of the cognitive science perspective on image memorability. *Rust & Mehrpour* (Trends in Cognitive Sciences, 2020)

## Prediction

- [**Parameter-Efficient Adaptation of Large Vision-Language Models for Video Memorability Prediction**](https://www.mdpi.com/1424-8220/25/6/1661) - State-of-the-art approach using QLoRA to fine-tune Qwen-VL model, achieving 0.744 Spearman correlation on Memento10k dataset. *Martín-Fernández et al.* (Sensors, 2025)

- [**MindMem: Multimodal for Predicting Advertisement Memorability Using LLMs and Deep Learning**](https://arxiv.org/abs/2502.18371) - Multimodal approach integrating textual, visual, and auditory data achieving 0.631 Spearman correlation on LAMBDA. Introduces MindMem-ReAd for LLM-based ad optimization with up to 74.12% memorability improvement. *Asgarian et al.* (arXiv, 2025)

- [**Unsupervised Memorability Modeling from Tip-of-the-Tongue Retrieval Queries**](https://arxiv.org/abs/2511.20854) - First large-scale unsupervised memorability dataset (82,000 videos) using tip-of-the-tongue retrieval queries from Reddit, enabling recall generation and multimodal ToT retrieval. *Bhattacharyya et al.* (arXiv, 2025)

- [**Long-Term Ad Memorability: Understanding & Generating Memorable Ads**](https://arxiv.org/abs/2309.00378) - First large-scale study of long-term ad memorability with LAMBDA dataset (1749 participants, 2205 ads, 276 brands). Introduces Henry model for prediction and SEED approach for memorable ad generation, releasing UltraLAMBDA dataset (5M ads). *Harini et al.* (WACV, 2025)

- [**Teaching Human Behavior Improves Content Understanding Abilities Of LLMs**](https://arxiv.org/abs/2411.01308) - Shows training LLMs on receiver behavior (likes, comments) improves content understanding across 46 video/image tasks on 26 benchmarks, releasing 750k annotated items. *Singh et al.* (arXiv, 2024)

- [**Modular Memorability: Tiered Representations for Video Memorability Prediction**](https://openaccess.thecvf.com/content/CVPR2023/html/Dumont_Modular_Memorability_Tiered_Representations_for_Video_Memorability_Prediction_CVPR_2023_paper.html) - Proposes M3-S model with modular architecture emulating the "pathway to memory" through four key steps: encoding, scene understanding, event understanding, and memory consolidation. *Dumont et al.* (CVPR, 2023)

- [**Seeing Eye to AI: Comparing Human Gaze and Model Attention in Video Memorability**](https://ieeexplore.ieee.org/document/10030889) - Analyzes spatiotemporal attention mechanisms by comparing CNN+Transformer model attention with human eye-tracking data during memory tasks. *Kumar et al.* (WACV, 2023)

- [**Defining Image Memorability Using the Visual Memory Schema**](https://ieeexplore.ieee.org/document/8715409) - Proposes Visual Memory Schema concept based on memorable regions identified by human observers during episodic memory tests. *Akagunduz et al.* (TPAMI, 2020)

- [**Image Memorability Prediction Using Depth and Motion Cues**](https://ieeexplore.ieee.org/document/9007618) - Deep learning model utilizing depth and optical flow information, achieving 2.44% improvement over prior state-of-the-art. *Basavaraju & Sur* (IEEE TCSS, 2020)

- [**Multimodal Memorability: Modeling Effects of Semantics and Decay on Video Memorability**](https://arxiv.org/abs/2009.02568) - Introduces Memento10k dataset with human annotations at different viewing delays, proposes mathematical formulation of memorability decay combining visual and semantic information. *Newman et al.* (ECCV, 2020)

- [**MemCat: a new category-based image set quantified on memorability**](https://peerj.com/articles/8169/) - Introduces MemCat, a category-based image set with 10K images across five categories with memorability scores based on 99 participants per image. *Goetschalckx & Wagemans* (PeerJ, 2019)

- [**VideoMem: Constructing, Analyzing, Predicting Short-Term and Long-Term Video Memorability**](https://openaccess.thecvf.com/content_ICCV_2019/html/Cohendet_VideoMem_Constructing_Analyzing_Predicting_Short-Term_and_Long-Term_Video_Memorability_ICCV_2019_paper.html) - Introduces VideoMem dataset (10,000 videos) with both short-term and long-term memorability annotations, achieving 0.494 correlation for short-term prediction. *Cohendet et al.* (ICCV, 2019)

- [**Annotating, Understanding, and Predicting Long-term Video Memorability**](https://dl.acm.org/doi/10.1145/3206025.3206056) - Proposes protocol for collecting long-term video memorability annotations, measuring memory from weeks to years after viewing. *Cohendet et al.* (ICMR, 2018)

- [**AMNet: Memorability Estimation with Attention**](https://ieeexplore.ieee.org/document/8578778) - End-to-end trainable deep network with visual attention mechanism that outperforms prior models on SUN Memorability and LaMem datasets. *Fajtl et al.* (CVPR, 2018)

- [**Show and Recall: Learning What Makes Videos Memorable**](https://openaccess.thecvf.com/content_ICCV_2017_workshops/w40/html/Shekhar_Show_and_Recall_ICCV_2017_paper.html) - Develops prediction model incorporating video content complexities, introduces video sub-shot memorability prediction task. *Shekhar et al.* (ICCVW, 2017)

- [**Intrinsic and extrinsic effects on image memorability**](https://www.sciencedirect.com/science/article/pii/S0042698915001017) - Comprehensive study on both intrinsic image properties and extrinsic factors affecting memorability. *Bylinskii et al.* (Vision Research, 2015)

- [**Understanding and Predicting Image Memorability at a Large Scale**](https://ieeexplore.ieee.org/document/7410596) - Introduces LaMem dataset (60,000 images) and shows CNNs achieve near-human consistency (0.64 correlation) in memorability prediction, with memorability manipulation capabilities. *Khosla et al.* (ICCV, 2015)

- [**What Makes an Object Memorable?**](https://ieeexplore.ieee.org/document/7410393) - First study of object-level memorability in images, analyzing visual factors and finding image memorability is greatly affected by its most memorable object. *Dubey et al.* (ICCV, 2015)

- [**Learning Computational Models of Video Memorability from fMRI Brain Imaging**](https://ieeexplore.ieee.org/document/6938869) - Novel framework integrating audiovisual features with brain fMRI data to learn computational models of video memorability. *Han et al.* (IEEE Transactions on Cybernetics, 2015)

- [**Modifying the Memorability of Face Photographs**](https://ieeexplore.ieee.org/document/6751394) - Method to automatically modify face photo memorability while preserving identity and other facial traits, achieving 74% accuracy in memorability manipulation. *Khosla et al.* (ICCV, 2013)

- [**The intrinsic memorability of face photographs**](https://psycnet.apa.org/record/2013-42046-001) - Demonstrates that face memorability is intrinsic and consistent across observers, exploring 20 personality and social traits but finding memorability is a distinct measure. *Bainbridge et al.* (Journal of Experimental Psychology: General, 2013)

- [**Relative spatial features for image memorability**](https://dl.acm.org/doi/10.1145/2502081.2502198) - Proposes Weighted Object Area and Relative Area Rank features that capture object-centric spatial characteristics correlated with memorability. *Kim et al.* (ACM MM, 2013)

- [**Memorability of natural scenes: The role of attention**](https://ieeexplore.ieee.org/document/6738041) - Investigates the relationship between visual attention and image memorability, showing attention-related features can improve prediction. *Mancas & Meur* (ICIP, 2013)

- [**Memorability of Image Regions**](https://papers.nips.cc/paper/2012/hash/98dce83da57b0395e163467c9dae521b-Abstract.html) - Probabilistic framework for modeling which local regions from an image may be forgotten, introducing memorability maps. *Khosla et al.* (NIPS, 2012)

- [**Understanding the Intrinsic Memorability of Images**](https://papers.nips.cc/paper/2011/hash/1f71e393b3809197ed66df836fe833e5-Abstract.html) - Analysis of image attributes that characterize memorability, finding that enclosed spaces with people are memorable while vistas are not. *Isola et al.* (NIPS, 2011)

- [**What makes an image memorable?**](https://ieeexplore.ieee.org/document/5995721) - Pioneering work showing that memorability is a stable property of images shared across viewers, introducing the first large-scale memorability study and prediction models. *Isola et al.* (CVPR, 2011)

## Generation and Modification

- [**Long-Term Ad Memorability: Understanding & Generating Memorable Ads**](https://arxiv.org/abs/2309.00378) - First large-scale study of long-term ad memorability with LAMBDA dataset (1749 participants, 2205 ads, 276 brands). Introduces Henry model for prediction and SEED approach for memorable ad generation, releasing UltraLAMBDA dataset (5M ads). *Harini et al.* (WACV, 2025)

- [**Changing the Image Memorability: From Basic Photo Editing to GANs**](https://ieeexplore.ieee.org/document/8803762) - Studies impact of both classical photo editing and GANs on memorability, exploring memorability as an attribute for conditional image generation. *Sidorov* (CVPRW, 2019)

- [**How to Make an Image More Memorable? A Deep Style Transfer Approach**](https://dl.acm.org/doi/10.1145/3078971.3078986) - Demonstrates automatic retrieval of style seeds to increase image memorability using deep neural style transfer. *Siarohin et al.* (ICMR, 2017)

- [**Modifying the Memorability of Face Photographs**](https://ieeexplore.ieee.org/document/6751394) - Method to automatically modify face photo memorability while preserving identity and other facial traits, achieving 74% accuracy in memorability manipulation. *Khosla et al.* (ICCV, 2013)

## Datasets

- [**LAMBDA**](https://behavior-in-the-wild.github.io/memorability) - Long-term advertisement memorability dataset with 1,749 participants, 2,205 ads covering 276 brands. *Harini et al.* (2023)

- [**UltraLAMBDA**](https://behavior-in-the-wild.github.io/memorability) - Large-scale automatically annotated ad dataset with 5 million advertisements for memorable ad generation. *Harini et al.* (2023)

- [**Memento10k**](https://memento.csail.mit.edu/) - Dynamic video memorability dataset with human annotations at different viewing delays, used for studying memorability decay over time. *Newman et al.* (2020)

- [**VideoMem**](https://github.com/TearsofTime/VideoMem) - 10,000 videos with both short-term and long-term memorability annotations measured at different delays. *Cohendet et al.* (2019)

- [**MemCat**](https://osf.io/28r9u/) - Category-based image set with 10,000 images across five categories (animal, food, landscape, sports, vehicle) with memorability scores from 99 participants per image. *Goetschalckx & Wagemans* (2019)

- [**LaMem**](http://memorability.csail.mit.edu/) - Large-scale image memorability dataset with 60,000 annotated images from diverse sources. *Khosla et al.* (2015)

## Workshops and Challenges

- [**MediaEval Predicting Video Memorability Task**](https://multimediaeval.github.io/editions/2022/) - Annual benchmark challenge for video memorability prediction, including short-term prediction and EEG-based prediction sub-tasks. *Multiple editions from 2018-2022*
  - [2022 Overview](https://arxiv.org/abs/2212.06516) - Introduces VideoMem dataset and EEG-based prediction sub-task. *Sweeney et al.*

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first. To add a paper or resource:

1. Make sure it's related to media memorability (images, videos, advertisements, faces, objects)
2. Add it to the appropriate section
3. Use the format: `[**Title**](link) - Brief description. *Authors* (Venue, Year)`
4. Ensure the link works and points to an official source (preferably DOI, arXiv, or conference proceedings)
5. Keep entries within each section sorted by year (newest first)

For major organizational changes, please open an issue first to discuss.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
