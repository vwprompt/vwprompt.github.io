# Visual Writing Prompts Dataset (VWP)

**[Website](https://vwprompt.github.io/)** | **[Github Repository](https://github.com/vwprompt/vwp)** | **[arXiv e-Print](https://arxiv.org/abs/2301.08571)**

<!-- Provide a quick summary of the dataset. -->

The Visual Writing Prompts (VWP) dataset contains almost 2K selected sequences of
movie shots, each including 5-10 images. The image sequences are aligned with a total of 12K stories which are collected via crowdsourcing given the image sequences and up to 5  grounded characters from the corresponding image sequence.

### Links

<!-- Provide the basic links for the dataset. -->

- **TACL 2023 Paper:** [Visual Writing Prompts: Character-Grounded Story Generation with Curated Image Sequences](https://doi.org/10.1162/tacl_a_00553)

# Announcement
We are presenting our paper at EACL poster session, 9:00, 03 May 2023. 

**30 Mar 2023.** The [first release](https://github.com/vwprompt/vwp/releases/tag/v1.0.0) of our dataset is online. 

**20 Jan 2023.** The pre MIT press version of our paper is on [arxiv](https://arxiv.org/abs/2301.08571v1). 

We will make the full dataset available in the [vwp repo](https://github.com/vwprompt/vwp) before our conference presentation. 

# Paper

### Summary

<!-- Provide a longer summary of what this dataset is. -->

The Visual Writing Prompts (VWP) dataset is designed to facilitate the development and testing of natural language processing models that generate stories based on sequences of images. This dataset comprises nearly 2,000 curated sequences of movie shots, each sequence containing between 5 to 10 images. These images are meticulously selected to ensure they depict coherent plots centered around one or more main characters, enhancing the visual narrative structure for story generation. Aligned with these image sequences are approximately 12,000 stories, which were written by crowd workers using Amazon Mechanical Turk. This setup aims to provide a rich, visually grounded storytelling context that helps models generate more coherent, diverse, and engaging stories.

# Dataset

<!-- This section provides a description of the dataset fields, and additional information about the dataset structure such as criteria used to create the splits, relationships between data points, etc. -->

- **Curated by:** Xudong Hong, Asad Sayeed, Khushboo Mehra, Vera Demberg, Bernt Schiele
- **Funded by:** See Acknowledgments in our paper
- **Language(s) (NLP):** English
- **License:** Apache License 2.0

## Structure

The dataset is in a CSV file. The explanation of each column is in [this table](https://github.com/vwprompt/vwp/blob/main/column_explain.csv).

## 

## Baseline Models

We also propose a character-based story generation model driven by coherence as a strong baseline. Evaluations show that our generated stories are more coherent, visually grounded, and more diverse than stories generated with the current state-of-the-art model.

# Citation

If you use this dataset in your work, please cite this article in TACL 2023:

Xudong Hong, Asad Sayeed, Khushboo Mehra, Vera Demberg, and Bernt Schiele. 2023. [Visual Writing Prompts: Character-Grounded Story Generation with Curated Image Sequences](https://aclanthology.org/2023.tacl-1.33). *Transactions of the Association for Computational Linguistics*, 11:565–581.

**BibTeX:**

```latex
@article{10.1162/tacl_a_00553,
    author = {Hong, Xudong and Sayeed, Asad and Mehra, Khushboo and Demberg, Vera and Schiele, Bernt},
    title = "{Visual Writing Prompts: Character-Grounded Story Generation with Curated Image Sequences}",
    journal = {Transactions of the Association for Computational Linguistics},
    volume = {11},
    pages = {565-581},
    year = {2023},
    month = {06},
    issn = {2307-387X},
    doi = {10.1162/tacl_a_00553},
    url = {https://doi.org/10.1162/tacl\_a\_00553},
    eprint = {https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl\_a\_00553/2134487/tacl\_a\_00553.pdf},
}
```

# Contact

Xudong Hong, [xLASTNAME@coli.uni-saarland.de](mailto:xLASTNAME@coli.uni-saarland.de)

# Disclaimer

All the images are extracted from [the movie shots from the MovieNet dataset](https://opendatalab.com/OpenDataLab/MovieNet/tree/main/raw). The copyrights of all movie shots belong to the original copyright holders which can be found in the IMDb page of each movie. The IMDb page is indicated by the index in the `imdb_id` column. For example, for the first row of our data, the `imdb_id` is `tt0112573` so the corresponding imdb page is https://www.imdb.com/title/tt0112573/companycredits/. Do not violate the copyrights while using these images. We only use these images for academic purposes. Please contact the author if you have any questions.



## Contact
For any questions or issues with the dataset, please open an issue on this Github page or contact [Xudong Hong](mailto:xhong@coli.uni-saarland.de).
