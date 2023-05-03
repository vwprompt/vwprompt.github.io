# Visual Writing Prompts Dataset (VWP)

## Announcement
We are presenting our paper at EACL poster session, 9:00, 03 May 2023. 

**30 Mar 2023.** The [first release](https://github.com/vwprompt/vwp/releases/tag/v1.0.0) of our dataset is online. 

**20 Jan 2023.** The pre MIT press version of our paper is on [arxiv](https://arxiv.org/abs/2301.08571v1). 

We will make the full dataset available in the [vwp repo](https://github.com/vwprompt/vwp) before our conference presentation. 


## Introduction
Current work on image-based story generation suffers from the fact that existing image sequence collections do not have coherent plots behind them. To improve visual story generation, we present a new image-grounded dataset, Visual Writing Prompts (VWP). 

## Dataset Description
The Visual Writing Prompts dataset contains almost 2K selected sequences of movie shots, each including 5-10 images. The image sequences are aligned with a total of 12K stories which were collected via crowdsourcing given the image sequences and a set of grounded characters from the corresponding image sequence. Our new image sequence collection and filtering process has allowed us to obtain stories that are more coherent and more diverse compared to previous work. 

## Baseline Model
We also propose a character-based story generation model driven by coherence as a strong baseline. Evaluations show that our generated stories are more coherent, visually grounded, and more diverse than stories generated with the current state-of-the-art model.

## Citation
The Visual Writing Prompts dataset is available for research purposes. If you use this dataset in your work, please cite the following arXiv pre-print before the release of this article in TACL 2023:
```
@misc{https://doi.org/10.48550/arxiv.2301.08571,
  doi = {10.48550/ARXIV.2301.08571},
  url = {https://arxiv.org/abs/2301.08571},
  author = {Hong, Xudong and Sayeed, Asad and Mehra, Khushboo and Demberg, Vera and Schiele, Bernt},
  keywords = {Computation and Language (cs.CL), Computer Vision and Pattern Recognition (cs.CV), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Visual Writing Prompts: Character-Grounded Story Generation with Curated Image Sequences},
  publisher = {arXiv},
  year = {2023},
  copyright = {Creative Commons Attribution 4.0 International}
}
```






## Contact
For any questions or issues with the dataset, please open an issue on this Github page or contact [Xudong Hong](mailto:xhong@coli.uni-saarland.de).
