# Visual Writing Prompts Dataset (VWP)

## Announcement
We will make the full dataset available in the [vwp repo](https://github.com/vwprompt/vwp) before our conference presentation. 

## Introduction
Current work on image-based story generation suffers from the fact that existing image sequence collections do not have coherent plots behind them. To improve visual story generation, we present a new image-grounded dataset, Visual Writing Prompts (VWP). 

## Dataset Description
The Visual Writing Prompts dataset contains almost 2K selected sequences of movie shots, each including 5-10 images. The image sequences are aligned with a total of 12K stories which were collected via crowdsourcing given the image sequences and a set of grounded characters from the corresponding image sequence. Our new image sequence collection and filtering process has allowed us to obtain stories that are more coherent and more diverse compared to previous work. 

## Baseline Model
We also propose a character-based story generation model driven by coherence as a strong baseline. Evaluations show that our generated stories are more coherent, visually grounded, and more diverse than stories generated with the current state-of-the-art model.

## Citation
The Visual Writing Prompts dataset is available for research purposes. If you use this dataset in your work, please cite the following paper:
```
@article{10.1162/tacl_a_00444,
    author = {Xudong Hong, Asad Sayeed, Khushboo Mehra, Vera Demberg and Bernt Schiele},
    title = "{Visual Writing Prompts:
Character-Grounded Story Generation with Curated Image Sequences}",
    journal = {Transactions of the Association for Computational Linguistics},
    volume = {11},
    year = {2023},
    month = {03},
    issn = {2307-387X},
    doi = {10.1162/tacl_a_00444},
    url = {https://doi.org/10.1162/tacl\_a\_00444},
    eprint = {https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl\_a\_00444/1986589/tacl\_a\_00444.pdf},
}
```






## Contact
For any questions or issues with the dataset, please open an issue on this Github page or contact [Xudong Hong](mailto:xhong@coli.uni-saarland.de).
